<template>
  <div class="container">
    <p>form-test</p>
    <div class="well tab-content">

      <div class="tab-pane active" id="post-object-form">

        <form action="http://localhost:8667/api/activity/activity/" method="POST" enctype="multipart/form-data" class="form-horizontal" novalidate="">
          <fieldset>
            <input type="hidden" name="csrfmiddlewaretoken" value="GouNwJ0Mk119VaWz2GgoONHEh1zmfCnFPspB1OguEGNB668QjP2VLbmNr5ssNOTY">





            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                Number of college
              </label>


              <div class="col-sm-10">
                <!--<input name="number_of_college" class="form-control" type="number" >-->
                <input name="number_of_college" class="form-control" type="number" v-model="infos.number_of_college">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                活动内容
              </label>


              <div class="col-sm-10">
                <textarea name="content" class="form-control" v-model="infos.content"></textarea>




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                开始时间
              </label>


              <div class="col-sm-10">
                <input name="start_date" class="form-control" type="datetime-local" v-model="infos.start_date">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                结束时间
              </label>


              <div class="col-sm-10">
                <input name="end_date" class="form-control" type="datetime-local" v-model="infos.end_date">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                Add money for benifit
              </label>


              <div class="col-sm-10">
                <input name="add_money_for_benifit" class="form-control" type="number" v-model="infos.add_money_for_benifit">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                Activity discount
              </label>


              <div class="col-sm-10">
                <input name="activity_discount" class="form-control" type="number" v-model="infos.activity_discount">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                Market discount
              </label>


              <div class="col-sm-10">
                <input name="market_discount" class="form-control" type="number" v-model="infos.market_discount">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                Number of order
              </label>


              <div class="col-sm-10">
                <input name="number_of_order" class="form-control" type="number" v-model="infos.number_of_order">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                Front image
              </label>


              <div class="col-sm-10">
                <input name="front_image" class="form-control" type="text" v-model="infos.front_image">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                Pay money
              </label>


              <div class="col-sm-10">
                <input name="pay_money" class="form-control" type="number" v-model="infos.pay_money">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                Name
              </label>


              <div class="col-sm-10">
                <input name="name" class="form-control" type="text" v-model="infos.name">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                访问人数
              </label>


              <div class="col-sm-10">
                <input name="watch_num" class="form-control" type="number" v-model="infos.watch_num">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                Attent num
              </label>


              <div class="col-sm-10">
                <input name="attent_num" class="form-control" type="number" value="">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                活动价格
              </label>


              <div class="col-sm-10">
                <input name="activity_price" class="form-control" type="number" value="">




              </div>
            </div>




            <div class="form-group ">

              <label class="col-sm-2 control-label ">
                市场价格
              </label>


              <div class="col-sm-10">
                <input name="market_price" class="form-control" type="number" value="">




              </div>
            </div>








            <div class="form-actions">
              <button class="btn btn-primary js-tooltip" title="" data-original-title="Make a POST request on the Activity resource">POST</button>
            </div>
          </fieldset>
        </form>

      </div>


      <div class="tab-pane" id="post-generic-content-form">

        <form action="/activity/activity/" method="POST" class="form-horizontal">
          <fieldset>



            <div class="form-group">
              <label for="id__content_type" class="col-sm-2 control-label">Media type:</label>
              <div class="col-sm-10">
                <select name="_content_type" data-override="content-type" id="id__content_type" class="form-control">
                  <option value="application/json" selected="">application/json</option>

                  <option value="application/x-www-form-urlencoded">application/x-www-form-urlencoded</option>

                  <option value="multipart/form-data">multipart/form-data</option>

                </select>
                <span class="help-block"></span>
              </div>
            </div>

            <div class="form-group">
              <label for="id__content" class="col-sm-2 control-label">Content:</label>
              <div class="col-sm-10">
      <textarea name="_content" cols="40" rows="10" data-override="content" id="id__content" class="form-control">{
    "number_of_college": null,
    "content": "",
    "start_date": null,
    "end_date": null,
    "add_money_for_benifit": null,
    "activity_discount": null,
    "market_discount": null,
    "number_of_order": null,
    "front_image": "",
    "pay_money": null,
    "name": "",
    "watch_num": null,
    "attent_num": null,
    "activity_price": null,
    "market_price": null
}</textarea>
                <span class="help-block"></span>
              </div>
            </div>


            <div class="form-actions">
              <button class="btn btn-primary js-tooltip" title="" data-original-title="Make a POST request on the Activity resource">POST</button>
            </div>
          </fieldset>
        </form>

      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "vue-form",
    props:['infos']
  }
</script>

<style scoped>

</style>
