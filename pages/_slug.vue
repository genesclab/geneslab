<template>
  <div>
    {{ data }}
    <b-menu label="Menu">
      <b-menu-list>
        <b-menu-item label="song2">
          test
        </b-menu-item>
        <b-menu-item icon="account" label="funker">
          test3
        </b-menu-item>
        <b-menu-item icon-pack="mdi" icon="account-alert" label="rout" >
          <b-icon icon="home" :type="{'is-primary':1}" size="is-large">
          </b-icon>
        </b-menu-item>
        <b-menu-item label="dont think">
        </b-menu-item>
      </b-menu-list>
    </b-menu>
  </div>
</template>

<script>
export default {
  asyncData({params}) {
    return { data: params.slug }
  },
}
</script>
