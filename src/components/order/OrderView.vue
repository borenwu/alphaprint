<template>
  <div class="col s12 m12 l6">
    <div class="card">
      <div class="card-content">
        <span class="cardTitle">任务信息</span><br>
        <div class="row">
          <form class="col s12">
            <div class="row">
              <div class="input-field col s6">
                <input id="client_name" type="text" class="validate">
                <label for="client_name">客户</label>
              </div>
            </div>

            <div class="row">
              <div class="input-field col s12">
                <input id="task_name" type="text" class="validate">
                <label for="task_name">印刷任务</label>
              </div>
            </div>

            <div class="row">
              <div class="input-field col s12">
                <input id="amount" type="number" class="validate">
                <label for="amount">印量</label>
              </div>
            </div>

            <div class="row">
              <div class="input-field col s12">
                <select>
                  <option value="" disabled selected>Choose your option</option>
                  <option value="1">Option 1</option>
                  <option value="2">Option 2</option>
                  <option value="3">Option 3</option>
                </select>
                <label>Materialize Select</label>
              </div>
            </div>

            <div class="row">
              <div class="input-field col s12">
                <textarea id="description" class="materialize-textarea"></textarea>
                <label for="description">任务描述</label>
              </div>
            </div>

            <div class="row">
              <div class="input-field col s12">
                <button class="btn waves-effect waves-light right cyan" type="submit" name="action">提交
                  <i class="material-icons right">send</i>
                </button>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
    input,label,textarea{
      font-family: "Microsoft YaHei UI";
      font-size: 15px;
      color: black;
    }
    .cardTitle{
      font-family: "Microsoft YaHei UI";
      font-size: 20px;
    }
</style>

<script>
    export default{
        data(){
            return{
                msg:'hello order'
            }
        },
        components:{

        }
    }
</script>
