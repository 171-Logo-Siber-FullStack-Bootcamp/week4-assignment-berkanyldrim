<template>
<!-- Page Content Start -->
    <div class="berkan">

        <div class="main-text"><p>Welcome to my VueJs Homework</p>
        
        <button class="btn btn-go"> <a class="link-go" href="https://github.com/171-Logo-Siber-FullStack-Bootcamp/week4-assignment-berkanyldrim">Go to Project Repository</a> </button>
        
        </div>
        

    </div>
<!-- Page Content END -->
</template>
<script>
    export default{
        name:"PageContent"
    }
</script>
<style>
.berkan{
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url(../../public/img/nature.jpg);
    background-position: center;
    background-size: cover;
    height: 100%;
}
.main-text{
    margin-top: -100px;
    display: block;
    
    font-size: 72px;
    font-weight: 600;
    color: white !important;
}
.btn-go{
    margin-left: 40%;
   border: solid 1px #505050;
    
    background-color: #203239;
    height: 60px;
    
    border-radius: 10px !important;
    
}
.link-go{
    
    text-decoration: none !important;
    color: white;
    font-weight: bold;

}
.link-go:hover{
    color: white;
    font-weight: bold;
}
</style>