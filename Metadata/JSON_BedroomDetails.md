<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.json.schema" id="_oSqAQODNEfC7ivsSxMkT5A" md:ref="resource.tech#UUID_TECH_JSON1?fileId=UUID_TECH_JSON1$type=tech$name=json?" internalVersion="v2.0.0">
  <node defType="com.stambia.json.rootObject" id="_oW5nEODNEfC7ivsSxMkT5A" name="BedroomDetails">
    <attribute defType="com.stambia.json.rootObject.encoding" id="_oXLT4ODNEfC7ivsSxMkT5A" value="UTF-8"/>
    <attribute defType="com.stambia.json.rootObject.reverseFilePath" id="_oXQzceDNEfC7ivsSxMkT5A" value="%{env:workspace_loc}%/Training/Files_In/Json/bedroomDetails.json"/>
    <attribute defType="com.stambia.json.rootObject.filePath" id="_tkr6kODNEfC7ivsSxMkT5A" value="%{env:workspace_loc}%/Training/Files_Out/Json/bedroomDetails.json"/>
    <node defType="com.stambia.json.array" id="_tDQBdeDNEfC7ivsSxMkT5A" name="bedroom_list" position="1">
      <node defType="com.stambia.json.object" id="_tDQBduDNEfC7ivsSxMkT5A" name="item" position="1">
        <node defType="com.stambia.json.value" id="_tDQBd-DNEfC7ivsSxMkT5A" name="bdr_id" position="1">
          <attribute defType="com.stambia.json.value.type" id="_tDQBeODNEfC7ivsSxMkT5A" value="number"/>
        </node>
        <node defType="com.stambia.json.value" id="_tDQBeeDNEfC7ivsSxMkT5A" name="bdr_number" position="2">
          <attribute defType="com.stambia.json.value.type" id="_tDQBeuDNEfC7ivsSxMkT5A" value="number"/>
        </node>
        <node defType="com.stambia.json.value" id="_tDQBe-DNEfC7ivsSxMkT5A" name="bdr_floor" position="3">
          <attribute defType="com.stambia.json.value.type" id="_tDQBfODNEfC7ivsSxMkT5A" value="number"/>
        </node>
        <node defType="com.stambia.json.value" id="_tDQBfeDNEfC7ivsSxMkT5A" name="bdr_bath" position="4">
          <attribute defType="com.stambia.json.value.type" id="_tDQBfuDNEfC7ivsSxMkT5A" value="number"/>
        </node>
        <node defType="com.stambia.json.value" id="_tDQBf-DNEfC7ivsSxMkT5A" name="bdr_shower" position="5">
          <attribute defType="com.stambia.json.value.type" id="_tDQBgODNEfC7ivsSxMkT5A" value="number"/>
        </node>
        <node defType="com.stambia.json.value" id="_tDQBgeDNEfC7ivsSxMkT5A" name="bdr_bar" position="6">
          <attribute defType="com.stambia.json.value.type" id="_tDQBguDNEfC7ivsSxMkT5A" value="number"/>
        </node>
        <node defType="com.stambia.json.value" id="_tDQBg-DNEfC7ivsSxMkT5A" name="bdr_bed_count" position="7">
          <attribute defType="com.stambia.json.value.type" id="_tDQBhODNEfC7ivsSxMkT5A" value="number"/>
        </node>
        <node defType="com.stambia.json.value" id="_tDQBheDNEfC7ivsSxMkT5A" name="bdr_phone_number" position="8">
          <attribute defType="com.stambia.json.value.type" id="_tDQBhuDNEfC7ivsSxMkT5A" value="string"/>
        </node>
        <node defType="com.stambia.json.value" id="_tDQBh-DNEfC7ivsSxMkT5A" name="bdr_type" position="9">
          <attribute defType="com.stambia.json.value.type" id="_tDQBiODNEfC7ivsSxMkT5A" value="string"/>
        </node>
        <node defType="com.stambia.json.array" id="_tDQBieDNEfC7ivsSxMkT5A" name="billing_lines" position="10">
          <node defType="com.stambia.json.object" id="_tDQBiuDNEfC7ivsSxMkT5A" name="item" position="1">
            <node defType="com.stambia.json.value" id="_tDQBi-DNEfC7ivsSxMkT5A" name="line_id" position="1">
              <attribute defType="com.stambia.json.value.type" id="_tDQBjODNEfC7ivsSxMkT5A" value="number"/>
            </node>
            <node defType="com.stambia.json.value" id="_tDQBjeDNEfC7ivsSxMkT5A" name="billing_id" position="2">
              <attribute defType="com.stambia.json.value.type" id="_tDQBjuDNEfC7ivsSxMkT5A" value="number"/>
            </node>
            <node defType="com.stambia.json.value" id="_tDQBj-DNEfC7ivsSxMkT5A" name="line_quantity" position="3">
              <attribute defType="com.stambia.json.value.type" id="_tDQBkODNEfC7ivsSxMkT5A" value="number"/>
            </node>
            <node defType="com.stambia.json.value" id="_tDQBkeDNEfC7ivsSxMkT5A" name="discount_rate" position="4">
              <attribute defType="com.stambia.json.value.type" id="_tDQBkuDNEfC7ivsSxMkT5A" value="number"/>
            </node>
            <node defType="com.stambia.json.value" id="_tDQBk-DNEfC7ivsSxMkT5A" name="discount_amount" position="5">
              <attribute defType="com.stambia.json.value.type" id="_tDQBlODNEfC7ivsSxMkT5A" value="number"/>
            </node>
            <node defType="com.stambia.json.value" id="_tDQBleDNEfC7ivsSxMkT5A" name="line_amount" position="6">
              <attribute defType="com.stambia.json.value.type" id="_tDQBluDNEfC7ivsSxMkT5A" value="number"/>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>