<template>
  <nav aria-label="Page navigation" class="flex justify-center mt-4">
    <ul class="flex items-center -space-x-px h-10 text-base">
      <li>
        <a href="#" @click.prevent="changePage(currentPage - 1)"
          :class="['flex items-center justify-center px-4 h-10 ms-0 leading-tight text-gray-500 bg-white border border-e-0 border-gray-300 rounded-s-lg hover:bg-gray-100 hover:text-gray-700 dark:bg-gray-800 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white']">
          <span class="sr-only">Previous</span>
          <svg class="w-3 h-3 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"
            viewBox="0 0 6 10">
            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M5 1 1 5l4 4" />
          </svg>
        </a>
      </li>
      <li v-for="page in pages" :key="page">
        <a href="#" @click.prevent="changePage(page)" :class="[
          'flex items-center justify-center px-4 h-10 leading-tight',
          page === currentPage
            ? 'text-blue-600 border border-blue-300 bg-blue-50 hover:bg-blue-100 hover:text-blue-700 dark:border-gray-700 dark:bg-gray-700 dark:text-white'
            : 'text-gray-500 bg-white border border-gray-300 hover:bg-gray-100 hover:text-gray-700 dark:bg-gray-800 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white'
        ]">
          {{ page }}
        </a>
      </li>
      <li>
        <a href="#" @click.prevent="changePage(currentPage + 1)"
          :class="['flex items-center justify-center px-4 h-10 leading-tight text-gray-500 bg-white border border-gray-300 rounded-e-lg hover:bg-gray-100 hover:text-gray-700 dark:bg-gray-800 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white']">
          <span class="sr-only">Next</span>
          <svg class="w-3 h-3 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"
            viewBox="0 0 6 10">
            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="m1 9 4-4-4-4" />
          </svg>
        </a>
      </li>
    </ul>
  </nav>
</template>

<script setup>
import { defineProps, defineEmits, computed } from 'vue';

// props 정의
const props = defineProps({
  pages: {
    type: Array,
    required: true
  },
  modelValue: {
    type: Number,
    required: true
  }
});
const emit = defineEmits(['update:modelValue']);

const currentPage = computed({
  get() {
    return props.modelValue;
  },
  set(val) {
    emit('update:modelValue', val);
  }
});

// 페이지 변경 함수
const changePage = (page) => {
  if (page >= 1 && page <= props.pages.length) {
    emit('update:modelValue', page);
  }
};
</script>


<style scoped></style>
