<template>
<div>
  <p></p>
  <input type="file" :name="uploadFieldName" :disabled="isSaving" @change="filesChange($event.target.name, $event.target.files); fileCount = $event.target.files.length"
     accept="trsx/*" class="button"> 
</div>
</template>


