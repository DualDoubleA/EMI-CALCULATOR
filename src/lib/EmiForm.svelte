<script lang="ts">
    import "carbon-components-svelte/css/all.css";
    import {Button, Slider, Form, FormLabel, FormItem} from 'carbon-components-svelte'
  
    let resultDeclared = false;
  </script>
  
  <main>
    
    <Form>
      
      <FormItem>
        <FormLabel>Principal</FormLabel>
        <Slider min={0} max={100000000000} maxLabel='not infinity' minLabel='0' />
      </FormItem>
      <FormItem>
        <FormLabel>Time</FormLabel>
        <Slider min={0} max={1000} maxLabel='1000 Years' minLabel='0' />
      </FormItem>
      <FormItem>
        <FormLabel>Rate</FormLabel>
        <Slider min={0} max={100} maxLabel='100%' minLabel='0' />
      </FormItem>
      <Button>Calculate</Button>
    </Form>
    {#if resultDeclared}
      <p>
        <li>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Omnis soluta iusto ea dolores assumenda labore error suscipit doloribus, dolorum odio. Tempore iusto sit officiis provident, hic aut enim similique ab!</li>
        <li>Quam qui fugiat cumque odio nobis alias dolorem, deserunt aspernatur tenetur esse similique officia dicta explicabo facilis vitae, ipsam tempore est id nostrum facere, praesentium accusamus laudantium? At, suscipit doloribus?</li>
        <li>Iusto accusantium veniam, velit fugiat dolor sapiente consequatur, debitis ratione necessitatibus sequi quia enim natus eligendi nemo doloremque illo voluptates dolorum asperiores nesciunt ullam nobis hic! Illo distinctio atque libero?</li>
        <li>Impedit obcaecati tempora vero voluptas unde optio corrupti ab eligendi modi sed, dolorem sit repellendus nam illo similique debitis molestiae assumenda magnam rem deleniti pariatur harum. Natus quos numquam dolorum?</li>
        <li>Deleniti excepturi sed quidem voluptas mollitia nostrum nemo. Soluta eum architecto doloribus ducimus repellat, ratione magni eveniet nihil rem facilis nam cupiditate excepturi laborum consequuntur eaque error eos. Provident, quam.</li>
        <li>Obcaecati necessitatibus totam blanditiis illo reprehenderit, alias ex architecto sint est aliquam aut earum eum optio labore ducimus sed. Odit enim, unde voluptas optio quasi exercitationem vitae animi beatae esse?</li>
        <li>Ad natus animi sed blanditiis illo totam culpa tempore voluptatum provident maxime, ducimus laboriosam neque nam quaerat delectus, esse voluptates voluptatem sapiente dolor iusto explicabo exercitationem in nisi. Natus, odit.</li>
        <li>Optio error dolorum magnam minima totam. Quo pariatur incidunt consectetur tempora dolore expedita esse autem explicabo nulla velit culpa, perspiciatis dolor aspernatur neque reiciendis iure reprehenderit. Magnam nobis voluptate tempore.</li>
        <li>Suscipit voluptatibus asperiores ullam consequuntur voluptates porro enim nihil. Blanditiis, eum accusantium. Optio tempora corrupti voluptatum facilis obcaecati quo? Cumque accusamus cum mollitia quaerat non neque incidunt consectetur enim! Ad.</li>
        <li>Ipsa neque consequatur minus eum temporibus iste molestiae, ex corrupti nesciunt doloremque impedit et ipsam cupiditate? Ipsum quae deleniti culpa modi, harum quisquam aperiam quos nostrum libero minima veniam similique.</li>
      </p>
    {/if}
  </main>
  
  <style>
  
  </style>
  