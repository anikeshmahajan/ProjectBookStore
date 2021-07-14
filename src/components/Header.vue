<template>
  <div class="header-content ">
    <div class="logo-content">
      <img
        class="image"
        src="../assets/education.svg"
        alt="logo"
        width="50"
        height="55"
      />
      <div><span class="add-text">BookStore</span></div>
      <div class="inputTag"> <input type="search"  placeholder="Search"></div>
        <div>
            <img src="../assets/supermarket.svg" alt="">
        </div>
    </div>
  </div>

</template>
<script>
export default {
  name: "Header",
};
</script>
<style scoped>


.header-content {
    background-color: #A03037;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}

.logo-content {
  display: flex;
  flex-direction: row;
  align-items: center;
  width: 80%;
}



.add-text {
  text-align: left;
  opacity: 1;
  transform: Titlecase;
  margin-left: 5px;
  font: normal normal normal 20px/26px Roboto;
  font-family: "Montserrat", sans-serif;
  letter-spacing: 0px;
  color:#FFFFFF;
}
.inputTag{
    margin-left: 42px;
}
input{
    border-radius: 3px;
    width: 490px;
    height: 33px;
}

</style>