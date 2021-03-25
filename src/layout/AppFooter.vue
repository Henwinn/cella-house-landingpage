<template>
    <footer class="footer has-cards">
        
        <div class="container">
            
            <hr>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div class="copyright">
                        &copy; {{year}}
                        <a target="_blank" rel="noopener">Cella House IT team</a> 
                    </div>
                </div>
                <div class="col-md-6">
                   
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
