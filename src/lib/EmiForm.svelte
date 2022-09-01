<script lang="ts">
    import "carbon-components-svelte/css/all.css";
    import {Button, Slider, Form} from 'carbon-components-svelte'
  </script>
  
  <main>
    
    <Form>
      <Slider min={0} max={100000000000} maxLabel='not infinity' minLabel='0' />
      <Button>Calculate</Button>
    </Form>
    
  </main>
  
  <style>
  
  </style>
  