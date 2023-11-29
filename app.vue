<template>
  <div>
    <BButton v-b-toggle.collapse-1 variant="primary">Toggle Collapse</BButton>

<BCollapse id="collapse-1">
  <BCard>
    <p class="card-text">Collapse contents Here</p>
    <BButton v-b-toggle.collapse-1-inner size="sm">Toggle Inner Collapse</BButton>
    <BCollapse id="collapse-1-inner" class="mt-2">
      <BCard>Hello!</BCard>
    </BCollapse>
  </BCard>
</BCollapse>
    
  </div>
</template>
