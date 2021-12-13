<template>
  <div class="container header">
     <div class="logo">
         <img src="../assets/dc-logo.png" alt="dc-logo">
     </div> 
     <nav>
         <ul>
             <li><a href="">link</a></li>
             <li><a href="">link</a></li>
             <li><a href="">link</a></li>
             <li><a href="">link</a></li>
             <li><a href="">link</a></li>
             <li><a href="">link</a></li>
             <li><a href="">link</a></li>
             <li><a href="">link</a></li>
         </ul>            
     </nav>
  </div>
</template>

<script>
export default {
 name: 'Header'
}
</script>

<style lang="scss" scoped>
    .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 80px;

        img {
            width: 60px;
        }

        ul {
            display: flex;
            justify-content: space-around;
            list-style: none;

            li {
                padding: 20px;

                a {
                    text-decoration: none;
                    text-transform: uppercase;                }
            }
        }
    }
</style>