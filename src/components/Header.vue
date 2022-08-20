<script>

export default {
    name: 'Header',

}
</script>



<template>
<div class="container">
<h1>Academic Research</h1>
<div class="bttn">
    <button  class="btn rep">Generate Report</button>
    <button  class="btn res">Add Research</button>
</div>
<!-- <div class="filt">
   
    <select name="Department" class="select" id="dep">
        <option value="a">Department</option>
        <option value="b">b</option>
        <option value="c">c</option>
    </select>

    <select name="FY" class="select" id="fy">
        <option value="a">FY</option>
        <option value="b">b</option>
        <option value="c">c</option>
    </select>

    <select name="div A" class="select" id="div-A">
        <option value="a">Div A</option>
        <option value="b">b</option>
        <option value="c">c</option>
    </select>
    <select name="Academic-year" class="select" id="year">
        <option value="a">Academic-year</option>
        <option value="b">b</option>
        <option value="c">c</option>
    </select>
</div> -->
</div>
</template>

<style scoped>
.select{
    padding: 12px 20px;
    margin: 2%;
    font-weight: bold;
    font-size: 15px;
    background-color: 	 #ccd6f6;
    border-radius: 5px;
}
.bttn{
    display: flex;
    justify-content: end;
}
.btn{
    padding: 12px 20px;
    font-size: 16px;
    margin: 5px;
    border-radius: 5px;
}
.rep{
    background-color: red;
    color: white;
    border-color: transparent;
}
.res{
    background-color: white;
    border-color: black;
}
</style>

