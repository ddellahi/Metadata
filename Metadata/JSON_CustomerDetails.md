<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.json.schema" id="_LIGxoODNEfC7ivsSxMkT5A" md:ref="resource.tech#UUID_TECH_JSON1?fileId=UUID_TECH_JSON1$type=tech$name=json?" internalVersion="v2.0.0">
  <node defType="com.stambia.json.rootObject" id="_LNK30ODNEfC7ivsSxMkT5A" name="CustomerDetails">
    <attribute defType="com.stambia.json.rootObject.encoding" id="_LNdLsODNEfC7ivsSxMkT5A" value="UTF-8"/>
    <attribute defType="com.stambia.json.rootObject.reverseJsonSchemaFilePath" id="_LNkgceDNEfC7ivsSxMkT5A" value="%{env:workspace_loc}%/Training/Files_In/Json/customerDetails.jsonschema"/>
    <attribute defType="com.stambia.json.rootObject.filePath" id="_ckd60ODNEfC7ivsSxMkT5A" value="%{env:workspace_loc}%/Training/Files_Out/Json/customerDetails.json"/>
    <node defType="com.stambia.json.array" id="_bctBheDNEfC7ivsSxMkT5A" name="customer_list">
      <node defType="com.stambia.json.object" id="_bctBhuDNEfC7ivsSxMkT5A" name="CustomerList">
        <node defType="com.stambia.json.value" id="_bctBh-DNEfC7ivsSxMkT5A" name="firstName">
          <attribute defType="com.stambia.json.value.type" id="_bctBiODNEfC7ivsSxMkT5A" value="string"/>
        </node>
        <node defType="com.stambia.json.value" id="_bctBieDNEfC7ivsSxMkT5A" name="lastName">
          <attribute defType="com.stambia.json.value.type" id="_bctBiuDNEfC7ivsSxMkT5A" value="string"/>
        </node>
        <node defType="com.stambia.json.array" id="_bctBi-DNEfC7ivsSxMkT5A" name="address">
          <node defType="com.stambia.json.object" id="_bctBjODNEfC7ivsSxMkT5A" name="Address">
            <node defType="com.stambia.json.value" id="_bctBjeDNEfC7ivsSxMkT5A" name="streetAddress">
              <attribute defType="com.stambia.json.value.type" id="_bctBjuDNEfC7ivsSxMkT5A" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_bctBj-DNEfC7ivsSxMkT5A" name="city">
              <attribute defType="com.stambia.json.value.type" id="_bctBkODNEfC7ivsSxMkT5A" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_bctBkeDNEfC7ivsSxMkT5A" name="state">
              <attribute defType="com.stambia.json.value.type" id="_bctBkuDNEfC7ivsSxMkT5A" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_bctBk-DNEfC7ivsSxMkT5A" name="postalCode">
              <attribute defType="com.stambia.json.value.type" id="_bctBlODNEfC7ivsSxMkT5A" value="string"/>
            </node>
          </node>
        </node>
        <node defType="com.stambia.json.array" id="_bctBleDNEfC7ivsSxMkT5A" name="phoneNumber">
          <node defType="com.stambia.json.object" id="_bctBluDNEfC7ivsSxMkT5A" name="PhoneNumber">
            <node defType="com.stambia.json.value" id="_bctBl-DNEfC7ivsSxMkT5A" name="type">
              <attribute defType="com.stambia.json.value.type" id="_bctBmODNEfC7ivsSxMkT5A" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_bctBmeDNEfC7ivsSxMkT5A" name="number">
              <attribute defType="com.stambia.json.value.type" id="_bctBmuDNEfC7ivsSxMkT5A" value="string"/>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>