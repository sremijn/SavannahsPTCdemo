<div class="background">
    <div class="layout">
       .<slot />
    </div>
</div>
<style> 
.background{
    padding: 110px;
    position: absolute; 
    inset: 0; 
    background-color:rgb(133, 210, 184); 
}
.layout{
    width: 100%; 
    max-width: 1024px; 
    margin: 0 auto; 
}

</style>