<template>
  <div class="container mx-auto text-base">
    <!-- header -->
    <div class="flex justify-between text-sm items-center bg-green-200 h-9">
      <div class="w-20 text-center">method</div>
      <div class="w-80 text-center">desc</div>
      <div class="w-96 text-center">url</div>
      <div class="w-32 text-center">response time</div>
      <div class="w-32 text-center">HTTP status</div>
      <div class="w-32 text-center">response type</div>
    </div>
    <!-- list -->
    <div class="flex justify-between text-sm items-center bg-green-50 h-9">
      <div class="w-20 text-center">GET</div>
      <div class="w-80 text-center">ユーザー一覧</div>
      <div class="w-96 text-center">/foo/users</div>
      <div class="w-32 text-center"><input type="number" class="w-16 text-right" value="300" /><span class="pl-2">ms</span></div>
      <div class="w-32 text-center"><input type="number" class="w-16 text-right" value="400" /></div>
      <div class="w-32 text-center">
        <select class="w-24">
          <option value="type1">type1</option>
          <option value="type2">type2</option>
          <option value="type3">type3</option>
        </select>
      </div>
    </div>
    <div class="flex justify-between text-sm items-center bg-green-100 h-9">
      <div class="w-20 text-center">GET</div>
      <div class="w-80 text-center">ユーザー一覧</div>
      <div class="w-96 text-center">/foo/users</div>
      <div class="w-32 text-center"><input type="number" class="w-16 text-right" value="300" /><span class="pl-2">ms</span></div>
      <div class="w-32 text-center"><input type="number" class="w-16 text-right" value="400" /></div>
      <div class="w-32 text-center">
        <select class="w-24">
          <option value="type1">type1</option>
          <option value="type2">type2</option>
          <option value="type3">type3</option>
        </select>
      </div>
    </div>
    <div class="flex justify-between text-sm items-center bg-green-50 h-9">
      <div class="w-20 text-center">GET</div>
      <div class="w-80 text-center">ユーザー一覧</div>
      <div class="w-96 text-center">/foo/users</div>
      <div class="w-32 text-center"><input type="number" class="w-16 text-right" value="300" /><span class="pl-2">ms</span></div>
      <div class="w-32 text-center"><input type="number" class="w-16 text-right" value="400" /></div>
      <div class="w-32 text-center">
        <select class="w-24">
          <option value="type1">type1nagainamaemamamamaeee</option>
          <option value="type2">type2</option>
          <option value="type3">type3</option>
        </select>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
