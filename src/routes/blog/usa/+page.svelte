<script>
    export let data;
  
    function goBack() {
      window.history.back();
    }
  
    function goNext() {
      window.location.href = '/bali'; // Update with the actual URL of your Bali blog page
    }
  </script>
  
  <style>
    .blog-detail {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }
  
    .blog-detail img {
      margin-top: 20px;
      border-radius: 8px;
      width: 100%;
      height: auto;
    }
  
    .blog-detail p {
      margin-top: 20px;
      line-height: 1.6;
    }
  
    .blog-detail h1 {
      text-align: center;
      margin-bottom: 20px;
    }
  
    .back-button, .next-button {
      position: fixed;
      bottom: 20px;
      padding: 10px 20px;
      background-color: #007BFF;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
  
    .back-button {
      left: 20px;
    }
  
    .next-button {
      right: 20px;
      text-decoration: none;
    }
  
    .back-button:hover, .next-button:hover {
      background-color: #0056b3;
    }
  </style>
  
  <div class="blog-detail">
    <h1 class="text-3xl font-bold">Planning my next trip ...</h1>
    
  </div>
  
  <button class="back-button" on:click={goBack}>Back</button>
  
  <!-- <a class="next-button" href="/blog/tokyo">Next</a> -->
  