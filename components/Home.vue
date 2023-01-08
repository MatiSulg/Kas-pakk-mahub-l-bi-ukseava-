<template>
  <div ref="MainHeader" class="MainHeader">
    <h1>Kas pakk mahub läbi ukseava?</h1>
  </div>
  <div ref="MainArea" class="MainArea">
    <div ref="SelectionBox" class="SelectionBox">
      <input ref="Searchbar" class="SearchBar" type="number"/>
      <div>

      </div>
    </div>
    <div ref="WorkBox" class="WorkBox">
      <div ref="DoorFrameBox">
        placeholder for doorframe visuals
        <div>
          <label>Ukseava kõrgus</label>
          <input ref="DoorFrameHeight" class="3digitNumber" type="number"/>
        </div>
        <div>
          <label>Ukseava laius</label>
          <input ref="DoorFrameWidth" class="3digitNumber" type="number"/>
        </div>
      </div>
      <div ref="PackageBox">
        placeholder for box visuals
        <div>
          <label>Pakki kõrgus</label>
          <input ref="HumanHeight" class="3digitNumber" type="number"/>
        </div>
        <div>
          <label>Pakki laius</label>
          <input ref="PackageWidth" class="3digitNumber" type="number"/>
        </div>
        <div>
          <label>Pakki sügavus</label>
          <input ref="PackageDepth" class="3digitNumber" type="number"/>
        </div>
      </div>
      <div ref="HumanSizeBox">
        placeholder for human shadow visuals
        <div>
          <label>Inimese kõrgus</label>
          <input ref="HumanHeight" class="3digitNumber" type="number"/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style>
  .WorkBox{
    display:flex;
  }
  .MainHeader{
    margin:auto;
    width:100%;
    height:50px;
    text-align:center;
  }
  .MainArea{
    display: flex;
  }
  .SelectionBox{
    background-color: green;
    height:500px;
  }
</style>
