<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="0"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="f00c5073-297c-4fe1-a149-5f558a8b89c8" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WWarningButton tag="button" top="38.85237258347979%" left="42.98725490196078%" v-bind:pill="false" size="md"
        text="Warning" type="button" v-bind:block="false" color="" theme="theme--light01" v-bind:squared="false"
        variant="warning" position="absolute" v-bind:isEnabled="true" background="" borderColor="#FFC107"
        ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF"
        ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#4285f4" ncDisableFontColor="#FFFFFF"
        ncFocusBorderColor="#4285f4" ncHoverBorderColor="#4285f4" ncDisableBorderColor="transparent"
        ncClickBackgroundColor="#4285f4" ncFocusBackgroundColor="#4285f4" ncHoverBackgroundColor="#4285f4"
        ncDisableBackgroundColor="#969696" id="268e76b7-f218-495b-bb1f-75837dd6fd91"
        v-bind:style="{'width':'','height':'','zIndex':2,'fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'1.4','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen3',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>