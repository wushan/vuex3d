<template>
  <div id="artboard">
    <div id="scene">
      <X3D id="x3dscene" version="3.0" PrimitiveQuality="High" showProgress="true" showStat="true" showLog="true" profile="Immersive" xmlns:xsd="http://www.w3.org/2001/XMLSchema-instance" xsd:noNamespaceSchemaLocation="http://www.web3d.org/specifications/x3d-3.0.xsd" width="100" height="100">
        <head>
          <meta name="filename" content="demo.x3d" />
          <meta name="generator" content="Blender 2.78 (sub 0)" />
        </head>
        <Scene>
          <NavigationInfo headlight="false"
                          visibilityLimit="0.0"
                          type='"EXAMINE", "ANY"'
                          avatarSize="0.25, 1.75, 0.75"
                          />
          <Background DEF="WO_World"
                  groundColor="0.92 0.92 0.92"
                  skyColor="0.97 0.97 0.97"
                  />
           <!--場景-->
          <!--<Collision DEF="DoNotCollideWithVisualizationWidget">
            <Group>
              <Group DEF="ArrowGreen">
                <Shape>
                  <Cylinder DEF="ArrowCylinder" radius=".055" top="false" height="10"> </Cylinder>
                  <Appearance DEF="Green">
                    <Material diffuseColor=".1 .6 .1" emissiveColor=".05 .2 .05"></Material>
                  </Appearance>
                </Shape>
                <Transform translation="0 1 0">
                  <Shape>
                    <Cone DEF="ArrowCone" bottomRadius=".05" height=".1"></Cone>
                    <Appearance USE="Green"></Appearance>
                  </Shape>
                </Transform>
              </Group>
            </Group>
          </Collision>
          <Transform translation="0 2.08 0">
            <Billboard>
              <Shape>
                <Appearance DEF="LABEL_APPEARANCE">
                  <Material diffuseColor="1 1 .3" emissiveColor=".33 .33 .1"></Material>
                </Appearance>
                <Text string="&quot;Y&quot;">
                  <FontStyle DEF="LABEL_FONT" family="&quot;SANS&quot;" justify="&quot;MIDDLE&quot; &quot;MIDDLE&quot;" size=".2"></FontStyle>
                </Text>
              </Shape>
            </Billboard>
          </Transform>
          <Transform rotation="0 0 1 -1.57079">
            <Group>
              <Group DEF="ArrowRed">
                <Shape>
                  <Cylinder USE="ArrowCylinder"></Cylinder>
                  <Appearance DEF="Red">
                    <Material diffuseColor=".7 .1 .1" emissiveColor=".33 0 0"></Material>
                  </Appearance>
                </Shape>
                <Transform translation="0 1 0">
                  <Shape>
                    <Cone USE="ArrowCone">
                      <Appearance USE="Red"></Appearance>
                    </Cone>
                  </Shape>
                </Transform>
                <Transform rotation="0 0 1 1.57079" translation=".072 1.1 0">
                  <Billboard>
                    <Shape>
                      <Appearance USE="LABEL_APPEARANCE"></Appearance>
                      <Text string="&quot;X&quot;">
                        <FontStyle USE="LABEL_FONT"></FontStyle>
                      </Text>
                    </Shape>
                  </Billboard>
                </Transform>
                <Transform rotation="1 0 0 1.57079">
                  <Group>
                    <Group DEF="ArrowBlue">
                      <Shape>
                        <Cylinder USE="ArrowCylinder"></Cylinder>
                        <Appearance DEF="Blue">
                          <Material diffuseColor=".3 .3 1" emissiveColor=".1 .1 .33"></Material>
                        </Appearance>
                      </Shape>
                    </Group>
                  </Group>
                </Transform>
                <Transform translation="0 1 0">
                  <Shape>
                    <Cone USE="ArrowCone"></Cone>
                    <Appearance USE="Blue"></Appearance>
                  </Shape>
                </Transform>
                <Transform rotation="1 0 0 -1.57079" translation="0 1.1 .072">
                  <Billboard>
                    <Shape>
                      <Appearance USE="LABEL_APPEARANCE"></Appearance>
                      <Text string="&quot;Z&quot;">
                        <FontStyle USE="LABEL_FONT"></FontStyle>
                      </Text>
                    </Shape>
                  </Billboard>
                </Transform>
              </Group>
            </Group>
          </Transform>-->
              
          <Transform DEF="SketchUp_TRANSFORM"
                    translation="0.000000 0.000000 0.000000"
                    scale="0.1 0.1 0.1"
                    rotation="0.000000 0.707107 0.707107 3.141593"
                    >
            <Transform DEF="group_2_TRANSFORM"
			           translation="-2.000000 2.000000 15"
			           scale="1.000000 1.000000 1.000000"
			           rotation="1.000000 0.000000 0.000000 0.000000"
			           >
              <Group DEF="group_ME_ID26">
                <Shape>
                  <Appearance>
                    <Material DEF="MA_material_4"
                              diffuseColor="0.429 0.929 1.000"
                              specularColor="0.401 0.401 0.401"
                              emissiveColor="0.000 0.000 0.000"
                              ambientIntensity="0.333"
                              shininess="0.098"
                              transparency="0.0"
                              />
                  </Appearance>
                  <IndexedFaceSet solid="true"
                                  coordIndex="0 1 2 -1 1 0 3 -1 4 5 6 -1 7 6 5 -1 12 13 14 -1 13 12 15 -1 16 17 18 -1 19 18 17 -1 22 23 24 -1 23 22 25 -1 26 27 28 -1 29 28 27 -1 31 32 33 -1 32 31 34 -1 35 36 37 -1 38 37 36 -1 40 41 42 -1 41 40 43 -1 44 45 46 -1 47 46 45 -1 48 49 50 -1 49 48 51 -1 52 53 54 -1 55 54 53 -1 "
                                  >
                    <Coordinate DEF="coords_ME_ID26"
                                point="7.000000 0.000000 12.000000 0.000000 2.000000 12.000000 0.000000 0.000000 12.000000 7.000000 2.000000 12.000000 7.000000 2.000000 12.000000 7.000000 0.000000 12.000000 0.000000 2.000000 12.000000 0.000000 0.000000 12.000000 0.000000 0.000000 12.000000 7.000000 0.000000 12.000000 7.000000 2.000000 12.000000 0.000000 2.000000 12.000000 7.000000 0.000000 12.000000 0.000000 0.000000 0.000000 7.000000 0.000000 0.000000 0.000000 0.000000 12.000000 0.000000 0.000000 12.000000 7.000000 0.000000 12.000000 0.000000 0.000000 0.000000 7.000000 0.000000 0.000000 0.000000 0.000000 0.000000 7.000000 0.000000 0.000000 7.000000 2.000000 0.000000 7.000000 0.000000 12.000000 7.000000 0.000000 0.000000 7.000000 2.000000 12.000000 7.000000 2.000000 12.000000 7.000000 2.000000 0.000000 7.000000 0.000000 12.000000 7.000000 0.000000 0.000000 7.000000 2.000000 0.000000 0.000000 2.000000 12.000000 7.000000 2.000000 0.000000 0.000000 2.000000 0.000000 7.000000 2.000000 12.000000 7.000000 2.000000 12.000000 0.000000 2.000000 12.000000 7.000000 2.000000 0.000000 0.000000 2.000000 0.000000 0.000000 2.000000 0.000000 0.000000 2.000000 12.000000 0.000000 0.000000 0.000000 0.000000 0.000000 12.000000 0.000000 2.000000 0.000000 0.000000 2.000000 0.000000 0.000000 2.000000 12.000000 0.000000 0.000000 0.000000 0.000000 0.000000 12.000000 7.000000 2.000000 0.000000 0.000000 0.000000 0.000000 0.000000 2.000000 0.000000 7.000000 0.000000 0.000000 7.000000 0.000000 0.000000 7.000000 2.000000 0.000000 0.000000 0.000000 0.000000 0.000000 2.000000 0.000000 "
                                />
                  </IndexedFaceSet>
                </Shape>
              </Group>
            </Transform>
            <Transform DEF="group_1_TRANSFORM"
                      translation="-5.000000 -5.000000 5.000000"
                      scale="1.000000 1.000000 1.000000"
                      rotation="1.000000 0.000000 0.000000 0.000000"
                      >
           
                <Group DEF="group_ME_ID15">
                  <Shape>
                    <Appearance>
                      <Material DEF="MA_material_2"
                                diffuseColor="1.000 0.514 0.112"
                                specularColor="0.401 0.401 0.401"
                                emissiveColor="0.000 0.000 0.000"
                                ambientIntensity="0.333"
                                shininess="0.098"
                                transparency="0.0"
                                />
                    </Appearance>
                    <IndexedFaceSet solid="true"
                                    coordIndex="0 1 2 -1 1 0 3 -1 4 5 6 -1 7 6 5 -1 12 13 14 -1 13 12 15 -1 16 17 18 -1 19 18 17 -1 22 23 24 -1 23 22 25 -1 26 27 28 -1 29 28 27 -1 31 32 33 -1 32 31 34 -1 35 36 37 -1 38 37 36 -1 40 41 42 -1 41 40 43 -1 44 45 46 -1 47 46 45 -1 48 49 50 -1 49 48 51 -1 52 53 54 -1 55 54 53 -1 "
                                    >
                      <Coordinate DEF="coords_ME_ID15"
                                  point="10.000000 9.000000 10.000000 0.000000 10.000000 10.000000 0.000000 9.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 9.000000 10.000000 0.000000 10.000000 10.000000 0.000000 9.000000 10.000000 0.000000 10.000000 10.000000 0.000000 9.000000 10.000000 10.000000 9.000000 10.000000 10.000000 10.000000 10.000000 0.000000 10.000000 10.000000 0.000000 9.000000 0.000000 0.000000 9.000000 10.000000 0.000000 10.000000 0.000000 0.000000 10.000000 0.000000 0.000000 10.000000 10.000000 0.000000 9.000000 0.000000 0.000000 9.000000 10.000000 0.000000 10.000000 0.000000 0.000000 9.000000 0.000000 10.000000 9.000000 10.000000 0.000000 9.000000 0.000000 10.000000 9.000000 0.000000 0.000000 9.000000 10.000000 0.000000 9.000000 10.000000 10.000000 9.000000 10.000000 0.000000 9.000000 0.000000 10.000000 9.000000 0.000000 10.000000 9.000000 0.000000 10.000000 10.000000 0.000000 10.000000 9.000000 10.000000 10.000000 9.000000 0.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 0.000000 10.000000 9.000000 10.000000 10.000000 9.000000 0.000000 10.000000 10.000000 0.000000 0.000000 10.000000 10.000000 10.000000 10.000000 0.000000 0.000000 10.000000 0.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 0.000000 10.000000 10.000000 10.000000 10.000000 0.000000 0.000000 10.000000 0.000000 10.000000 10.000000 0.000000 0.000000 9.000000 0.000000 0.000000 10.000000 0.000000 10.000000 9.000000 0.000000 10.000000 9.000000 0.000000 10.000000 10.000000 0.000000 0.000000 9.000000 0.000000 0.000000 10.000000 0.000000 "
                                  />
                    </IndexedFaceSet>
                  </Shape>
                </Group>
              </Transform>
            
            <Transform DEF="group_0_TRANSFORM"
                      translation="-5 -5 -5"
                      scale="1.000000 1.000000 1.000000"
                      rotation="1.000000 0.000000 0.000000 0.000000"
                      >
              
                <Group DEF="group_ME_ID4">
                  <Shape>
                    <Appearance>
                      <Material DEF="MA_material_3"
                                diffuseColor="1.000 0.992 0.466"
                                specularColor="0.401 0.401 0.401"
                                emissiveColor="0.000 0.000 0.000"
                                ambientIntensity="0.333"
                                shininess="0.098"
                                transparency="0.0"
                                />
                    </Appearance>
                    <IndexedFaceSet solid="true"
                                    coordIndex="0 1 2 -1 1 0 3 -1 4 5 6 -1 7 6 5 -1 12 13 14 -1 13 12 15 -1 16 17 18 -1 19 18 17 -1 22 23 24 -1 23 22 25 -1 26 27 28 -1 29 28 27 -1 31 32 33 -1 32 31 34 -1 35 36 37 -1 38 37 36 -1 40 41 42 -1 41 40 43 -1 44 45 46 -1 47 46 45 -1 48 49 50 -1 49 48 51 -1 52 53 54 -1 55 54 53 -1 "
                                    >
                      <Coordinate DEF="coords_ME_ID4"
                                  point="10.000000 0.000000 10.000000 0.000000 10.000000 10.000000 0.000000 0.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 0.000000 10.000000 0.000000 10.000000 10.000000 0.000000 0.000000 10.000000 0.000000 10.000000 10.000000 0.000000 0.000000 10.000000 10.000000 0.000000 10.000000 10.000000 10.000000 10.000000 0.000000 10.000000 10.000000 0.000000 0.000000 0.000000 0.000000 0.000000 10.000000 0.000000 10.000000 0.000000 0.000000 10.000000 0.000000 0.000000 10.000000 10.000000 0.000000 0.000000 0.000000 0.000000 0.000000 10.000000 0.000000 10.000000 0.000000 0.000000 0.000000 0.000000 10.000000 0.000000 10.000000 0.000000 0.000000 0.000000 10.000000 0.000000 0.000000 0.000000 0.000000 10.000000 0.000000 0.000000 10.000000 10.000000 0.000000 10.000000 0.000000 0.000000 0.000000 10.000000 0.000000 0.000000 10.000000 0.000000 0.000000 10.000000 10.000000 0.000000 10.000000 0.000000 10.000000 10.000000 0.000000 0.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 0.000000 10.000000 0.000000 10.000000 10.000000 0.000000 0.000000 10.000000 10.000000 0.000000 0.000000 10.000000 10.000000 10.000000 10.000000 0.000000 0.000000 10.000000 0.000000 10.000000 10.000000 10.000000 10.000000 10.000000 10.000000 0.000000 10.000000 10.000000 10.000000 10.000000 0.000000 0.000000 10.000000 0.000000 10.000000 10.000000 0.000000 0.000000 0.000000 0.000000 0.000000 10.000000 0.000000 10.000000 0.000000 0.000000 10.000000 0.000000 0.000000 10.000000 10.000000 0.000000 0.000000 0.000000 0.000000 0.000000 10.000000 0.000000 "
                                  />
                    </IndexedFaceSet>
                  </Shape>
                </Group>
              
            </Transform>
          </Transform>
          <Transform DEF="Lamp_TRANSFORM"
                    translation="-4.076245 5.903862 1.005454"
                    scale="1.000000 1.000000 1.000000"
                    rotation="-0.498084 -0.762016 -0.413815 1.513875"
                    >
            <PointLight DEF="LA_Lamp"
                        ambientIntensity="0.3000"
                        color="1.0000 1.0000 1.0000"
                        intensity="0.8"
                        radius="30.0000" 
                        location="-0.0000 -0.0000 0.0000"
                        />
          </Transform>
          <Transform DEF="Camera_TRANSFORM"
                translation="-7.481132 5.343665 -6.507640"
                scale="1.000000 1.000000 1.000000"
                rotation="-0.098233 -0.968789 -0.227591 2.349487"
                >
            <Viewpoint DEF="CA_Camera"
                      centerOfRotation="0 0 0"
                      position="-0.00 -0.00 0.00"
                      orientation="-0.00 -0.47 -0.88 0.00"
                      fieldOfView="0.858"
                      />
          </Transform>
        </Scene>
      </X3D>
    </div>
    <div id="attributes">
      <aside>
        <p>Selected Size</p>
        <p v-if="dimension">W: {{dimension.w}} / H: {{dimension.h}} / D: {{dimension.d}}</p>
      </aside>
    </div>
  </div>
</template>

<script>
export default {
  name: 'x3d',
  data () {
    return {
      selectedCoords: null,
      points: [],
      indexedface: [],
      diameter: {
        x: 0,
        y: 0,
        z: 0
      }
    }
  },
  created () {
    window.x3dom.runtime.ready = () => {
      console.log('initial')
      var $element = document.getElementById('x3dscene')
      // Adding the click event
      $element.addEventListener('click', (event) => {
        // Get the position of the mouse in the canvas
        console.log('clicked')
        var canvasPos = $element.runtime.mousePosition(event)
        // Return an array of shape elements contained in a rect on the canvas (x1,y1 and x2,y2)
        var picked = $element.runtime.pickRect(canvasPos[0], canvasPos[1], canvasPos[0], canvasPos[1])
        if (picked.length) {
          // do whatever you want
          var indexedface = picked[0].querySelectorAll('indexedfaceset')[0].getAttribute('coordindex').replace(/-1/g, '').replace(/ {2}/g, ' ').split(' ')
          var points = picked[0].querySelectorAll('coordinate')[0].getAttribute('point').split(' ')
          this.indexedface = indexedface
          this.points = this.pointsToArray(points)
        }
      }, false)

      // All points
      // for (var transform of $element.querySelectorAll('transform')) {
      //   if (transform.querySelectorAll('group')) {
      //     console.log('xx')
      //   }
      // }
      var wholePoints = []
      for (var pointArray of $element.querySelectorAll('coordinate')) {
        wholePoints = wholePoints.concat(this.pointsToArray(pointArray.getAttribute('point').split(' ')))
      }
      var xArray = []
      var yArray = []
      var zArray = []
      for (var compare of wholePoints) {
        xArray.push(parseInt(compare.x))
        yArray.push(parseInt(compare.y))
        zArray.push(parseInt(compare.z))
      }
      this.diameter.x = xArray.sort(this.sortNumbers)
      this.diameter.y = yArray.sort(this.sortNumbers)
      this.diameter.z = zArray.sort(this.sortNumbers)
    }
  },
  methods: {
    pointsToArray (el) {
      var size = 3
      var originArray = el || []
      var newArray = []
      for (var i = 0; i < originArray.length; i += size) {
        var point = {
          x: 0,
          y: 0,
          z: 0
        }
        for (var pair = 0; pair < originArray.slice(i, i + size).length; pair++) {
          // console.log(originArray.slice(i, i + size)[pair])
          switch (pair) {
            case 0:
              point.x = originArray.slice(i, i + size)[pair]
              break
            case 1:
              point.y = originArray.slice(i, i + size)[pair]
              break
            case 2:
              point.z = originArray.slice(i, i + size)[pair]
              break
          }
        }
        newArray.push(point)
      }
      return newArray
    },
    sortNumbers (x, y) {
      return x - y
    }
  },
  computed: {
    surface () {
      if (this.indexedface.length) {
        var newArray = []
        var triangles = []
        for (var surface of this.indexedface) {
          newArray.push(this.points[surface])
        }
        var size = 3
        var originArray = newArray || []
        // console.log(originArray.length)
        for (var i = 0; i < originArray.length; i += size) {
          triangles.push(originArray.slice(i, i + size))
        }
        return triangles
      }
    },
    dimension () {
      var xPair = []
      var yPair = []
      var zPair = []
      if (this.surface) {
        for (var point of this.surface[0]) {
          xPair.push(parseInt(point.x))
          yPair.push(parseInt(point.y))
        }
      }
      if (this.surface) {
        for (var zpoint of this.surface[4]) {
          zPair.push(parseInt(zpoint.z))
        }
      }
      return {
        ww: xPair.sort(this.sortNumbers),
        hh: yPair.sort(this.sortNumbers),
        dd: zPair.sort(this.sortNumbers),
        w: xPair.sort(this.sortNumbers)[2] - xPair.sort(this.sortNumbers)[0],
        h: yPair.sort(this.sortNumbers)[2] - yPair.sort(this.sortNumbers)[0],
        d: zPair.sort(this.sortNumbers)[2] - zPair.sort(this.sortNumbers)[0]
      }
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import '../assets/styles/x3dom';
#artboard {
  height: calc(100vh - 250px);
  display: flex;
  #scene {
    flex: 1;
  }
  #attributes {
    width: 300px;
    position: relative;
    box-shadow: 0 0 24px rgba(0,0,0,0.33);
  }
}
</style>
