<template>
  <section>
    <div class="row at-row flex-center flex-middle">
      <div class="col-lg-24">
        <hr class="footspace">
      </div>
    </div>

    <div class="row at-row flex-center flex-middle">
      <div class="col-lg-24">
        <img src="/static/img/msft_logo.png">
      </div>
    </div>

    <div class="row at-row flex-center flex-middle">
      <div class="col-lg-6">
      </div>
      <div class="col-lg-12 credits">
        Azure Blackbelt Team
      </div>
      <div class="col-lg-6">
      </div>
    </div>

   <div class="row at-row flex-center flex-middle">
      <div class="col-lg-24">
        <h1>
          j4kio Rocks!
          </h1>
      </div>
   </div>
  </section>
</template>

<script>
  export default {
    data() {
      return {
        imageTag: process.env.IMAGE_TAG,
        imageDate: process.env.IMAGE_BUILD_DATE,
        k8sNodeName: process.env.KUBE_NODE_NAME,
        k8sPodName: process.env.KUBE_POD_NAME,
        k8sPodIp: process.env.KUBE_POD_IP
      };
    }
  };
</script>