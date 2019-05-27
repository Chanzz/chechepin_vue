<template>
  <div>
    <p>form-test</p>
    <form action="#" data-method="PUT" enctype="multipart/form-data" class="form-horizontal"
          novalidate="">
      <fieldset>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            Number of college
          </label>
          <div class="col-sm-10">
            <input name="number_of_college" class="form-control" type="number" value="9">
          </div>
        </div>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            活动内容
          </label>
          <div class="col-sm-10">
            <textarea name="content" class="form-control">装潢大礼包¥5,000，美容代金劵¥5,000，1年无限洗车¥2,000，安防套装¥1,000，最高置换补贴¥3,000，保险补贴¥2,000</textarea>
          </div>
        </div>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            开始时间
          </label>
          <div class="col-sm-10">
            <input name="start_date" class="form-control" type="datetime-local" value="2018-08-25T19:21:00+08:00">
          </div>
        </div>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            结束时间
          </label>
          <div class="col-sm-10">
            <input name="end_date" class="form-control" type="datetime-local" value="2019-04-28T19:21:00+08:00">
          </div>
        </div>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            Add money for benifit
          </label>
          <div class="col-sm-10">
            <input name="add_money_for_benifit" class="form-control" type="number" value="10000.0">
          </div>
        </div>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            Activity discount
          </label>
          <div class="col-sm-10">
            <input name="activity_discount" class="form-control" type="number" value="20000.0">
          </div>
        </div>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            Market discount
          </label>
          <div class="col-sm-10">
            <input name="market_discount" class="form-control" type="number" value="15000.0">
          </div>
        </div>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            Number of order
          </label>
          <div class="col-sm-10">
            <input name="number_of_order" class="form-control" type="number" value="22">
          </div>
        </div>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            Front image
          </label>
          <div class="col-sm-10">
            <input name="front_image" class="form-control" type="text" value="activity_image/activity_image1.png">
          </div>
        </div>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            Pay money
          </label>
          <div class="col-sm-10">
            <input name="pay_money" class="form-control" type="number" value="0.0">
          </div>
        </div>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            Name
          </label>
          <div class="col-sm-10">
            <input name="name" class="form-control" type="text" value="1">
          </div>
        </div>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            访问人数
          </label>
          <div class="col-sm-10">
            <input name="watch_num" class="form-control" type="number" value="976">
          </div>
        </div>
        <div class="form-group ">
          <label class="col-sm-2 control-label ">
            Attent num
          </label>
          <div class="col-sm-10">
            <input name="attent_num" class="form-control" type="number" value="9">
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
          <button class="btn btn-primary js-tooltip" title=""
                  data-original-title="Make a PUT request on the Activity Detail resource">PUT
          </button>
        </div>
      </fieldset>
    </form>
  </div>
</template>

<script>
  export default {
    name: "vue-form"
  }
</script>

<style scoped>

</style>
