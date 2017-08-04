<context>
  <input pattern="(hello|hi) *">
    <output value="Hello $UserName!" if="full($UserName)"/>

    <context if="empty($UserName)">
      <output value="Hi! What is your name?"/>

      <input pattern="$Text">
        <var name="UserName" value="$Text" scope="user"/>
        <output value="Nice to meet you $UserName!"/>
      </input>

    </context>
  </input>
</context>
