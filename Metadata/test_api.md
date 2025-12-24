<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.http.rest" id="_gsrXQMrdEfCoseW7gaOR2A" name="test_api" md:ref="resource.tech#UUID_TECH_HTTPREST?fileId=UUID_TECH_HTTPREST$type=tech$name=HttpRest?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.http.rest.module" id="_gs1vUMrdEfCoseW7gaOR2A" value="HttpRest"/>
  <attribute defType="com.stambia.http.rest.reverseUrl" id="_l9RHIcrdEfCoseW7gaOR2A" value="https://jsonplaceholder.typicode.com"/>
  <attribute defType="com.stambia.http.rest.url" id="_So6sIMreEfCoseW7gaOR2A" value="https://jsonplaceholder.typicode.com"/>
  <node defType="com.stambia.http.rest.path" id="_mSrWcMrdEfCoseW7gaOR2A">
    <attribute defType="com.stambia.http.rest.path.path" id="_sAnwsMrdEfCoseW7gaOR2A" value="/posts/1"/>
    <node defType="com.stambia.http.rest.operation" id="_rge4EcrdEfCoseW7gaOR2A">
      <attribute defType="com.stambia.http.rest.operation.method" id="_t_BXEMrdEfCoseW7gaOR2A" value="GET"/>
    </node>
  </node>
  <node defType="com.stambia.http.rest.path" id="_So3o2MreEfCoseW7gaOR2A">
    <attribute defType="com.stambia.http.rest.path.path" id="_So3o2creEfCoseW7gaOR2A" value="/posts/{id}"/>
    <node defType="com.stambia.http.rest.operation" id="_So3o2sreEfCoseW7gaOR2A">
      <attribute defType="com.stambia.http.rest.operation.method" id="_So3o28reEfCoseW7gaOR2A" value="GET"/>
      <node defType="com.stambia.http.rest.parameters" id="_So3o3MreEfCoseW7gaOR2A">
        <node defType="com.stambia.http.rest.parameter" id="_So3o3creEfCoseW7gaOR2A" name="id">
          <attribute defType="com.stambia.http.rest.parameter.allowEmptyValue" id="_So3o3sreEfCoseW7gaOR2A" value="true"/>
          <attribute defType="com.stambia.http.rest.parameter.location" id="_So3o38reEfCoseW7gaOR2A" value="path"/>
        </node>
      </node>
      <node defType="com.stambia.http.rest.responses" id="_So3o4MreEfCoseW7gaOR2A">
        <node defType="com.stambia.http.rest.response" id="_So3o4creEfCoseW7gaOR2A">
          <attribute defType="com.stambia.http.rest.response.code" id="_ARyfoMrlEfCoseW7gaOR2A" value="default"/>
          <node defType="com.stambia.http.rest.content" id="_So4P9MreEfCoseW7gaOR2A">
            <attribute defType="com.stambia.http.rest.content.mediaType" id="_So4P9creEfCoseW7gaOR2A" value="JSON"/>
            <attribute defType="com.stambia.http.rest.content.contentType" id="_So4P9sreEfCoseW7gaOR2A" value="application/json"/>
            <node defType="com.stambia.json.rootObject" id="_So4P98reEfCoseW7gaOR2A" name="root">
              <node defType="com.stambia.json.value" id="_So4P-MreEfCoseW7gaOR2A" name="id" position="2">
                <attribute defType="com.stambia.json.value.type" id="_So4P-creEfCoseW7gaOR2A" value="number"/>
              </node>
              <node defType="com.stambia.json.value" id="_So4P-sreEfCoseW7gaOR2A" name="body" position="4">
                <attribute defType="com.stambia.json.value.type" id="_So4P-8reEfCoseW7gaOR2A" value="string"/>
              </node>
              <node defType="com.stambia.json.value" id="_So4P_MreEfCoseW7gaOR2A" name="title" position="3">
                <attribute defType="com.stambia.json.value.type" id="_So4P_creEfCoseW7gaOR2A" value="string"/>
              </node>
              <node defType="com.stambia.json.value" id="_So4P_sreEfCoseW7gaOR2A" name="userId" position="1">
                <attribute defType="com.stambia.json.value.type" id="_So4P_8reEfCoseW7gaOR2A" value="number"/>
              </node>
            </node>
          </node>
          <node defType="com.stambia.http.rest.respinfos" id="_XQ5KksrjEfCoseW7gaOR2A">
            <node defType="com.stambia.http.rest.respinfo" id="_YMURAMrjEfCoseW7gaOR2A">
              <attribute defType="com.stambia.http.rest.respinfo.type" id="_ZND8UMrjEfCoseW7gaOR2A" value="statusCode"/>
            </node>
            <node defType="com.stambia.http.rest.respinfo" id="_4tgrUMrjEfCoseW7gaOR2A">
              <attribute defType="com.stambia.http.rest.respinfo.type" id="_5Zu4IMrjEfCoseW7gaOR2A" value="reasonPhrase"/>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>