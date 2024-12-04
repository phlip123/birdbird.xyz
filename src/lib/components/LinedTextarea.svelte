<script>
    export let value = '';
    export let rows = 10;
    export let placeholder = '';
  </script>
  
  <textarea 
    bind:value 
    {rows} 
    {placeholder}
    class="lined-paper"
  />
  
  <style>
    .lined-paper {
      background-image: linear-gradient(#f5f5f5 49px, #ccc 0);
      background-size: 100% 50px;
      line-height: 50px;
      padding: 0 0 0 20px;
      font-family: 'Courier New', monospace;
      font-size: 16px;
      border: 1px solid #dedede;
      width: 100%;
      resize: none;
    }
  </style>