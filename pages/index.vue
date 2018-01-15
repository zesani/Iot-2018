<template>
  <section class="container-fluid">
    <div class="container">
    <div class="row">
      <div class="col-sm-12">
       <img src="../static/logo-02-01.png" style="width:100%; margin-top:-5%;" alt="">
          <div class="">
            <hr>
            <h1 style="color:#1B1464;" class="text-center">กำหนดการฝึกอบรม</h1>
            <p style=" text-align: justify;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;โครงการอบรมเชิงปฏิบัติการ เรื่อง "พัฒนาศักยภาพทุนมนุษย์เพื่อก้าวไปสู่ Thailand 4.0"
                จัดขึ้นโดยภาควิชาเทคโนโลยีสารสนเทศ คณะเทคโนโลยีและการจัดการอุตสาหกรรม มหาวิทยาลัยเทคโนโลยีพระจอมเกล้าพระนครเหนือ
                เนื่องจากปัจจุบันเทคโนโลยีทางด้าน IoT (Internet of Things) เป็นสิ่งที่น่าสนใจ และถูกนำมาพัฒนาใช้ในอุตสาหกรรมต่างๆ ของการผลิต การพาณิชย์อิเล็กทรอนิกส์ รวมไปถึงการสร้าง Data Centers
                เตรียมพบกับเทคโนโยนีที่น่าสนใจ ปูพื้นฐานทางด้าน IoT ตั้งแต่ ขั้น Basic จนถึง Advance โดยวิทยากรผู้เชี่ยวชาญ เรียนรู้การเขียนโปรแกรมบน Arduino IDE ทำงานร่วมกับ NodeMCU, IoT Could Service, การประยุกต์ใช้งาน Sensor
                และ อื่นๆ อีกมากมาย (อบรมฟรีไม่มีค่าใช้จ่าย)</p>
                <table class="table table-hover text-center" style="text-align: justify;">
                  <thead>
                    <tr class="colorhead">
                      <th scope="col">รุ่นที่ </th>
                      <th scope="col">วัน</th>
                      <th scope="col">สถานที่</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <th scope="row">1</th>
                      <td>วันที่ 15 - 18 กุมภาพันธ์ 2561 </td>
                      <td>ณ โรงแรมแอมบาสเดอร์ ซิตี้ จอมเทียน พัทยา จังหวัดชลบุรี</td>
                    </tr>
                    <tr>
                      <th scope="row">2</th>
                      <td>วันที่ 19 - 22 มีนาคม 2561 </td>
                      <td>ณ มหาวิทยาลัยเทคโนโลยีพระจอมเกล้าพระนครเหนือ วิทยาเขตปราจีนบุรี</td>
                    </tr>
                    <tr>
                      <th scope="row">3</th>
                      <td>วันที่ 29 มีนาคม - 1 เมษายน 2561</td>
                      <td>ณ มหาวิทยาลัยเทคโนโลยีพระจอมเกล้าพระนครเหนือ วิทยาเขตระยอง</td>
                    </tr>
                    <tr>
                      <th scope="row">4</th>
                      <td>วันที่ 19 - 22 เมษายน 2561 </td>
                      <td>ณ โรงแรมแอมบาสเดอร์ ซิตี้ จอมเทียน พัทยา จังหวัดชลบุรี</td>
                    </tr>
                  </tbody>
                </table>
          </div>
      </div>
    </div>
  </div>
  </section>
  </template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.colorhead{
  color: #65A8DA;
}
</style>
