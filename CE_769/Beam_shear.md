# Notes on Beam Shear Design (Week 3)

## General Cases
1. Allowable shear not exceeded; no shear reinforcement required
2. Shear exceeds allowable amount; steel shear reinforcement needed

### General Behavior of Masonry Beams
* Without web reinforcement, very similar to concrete
1. Diagonal tension forces are present in members where shear is highest
2. Combined effect of longitudinal tension and tangential shear stress
3. Shear design analysis and criteria have been based on tests and experience and the allowable stresses are conservative. Beam becomes more ductile with shear reinforcement
4. Failure occures through head and bed joints (stair step) or bed joints sliding at renfirocing through bond failure
5. Most flexural members will have a single allowable stress

### Beams
1. If the allowable shear in beams is not exceeded, no shear reinforcing needed
2. If the allowable shear is exceeded, the shear stress is divided between the steel and masonry per equations
3. The beam geomgetry or material strengths must be readjusted if the shear stress exceeds the allowable stress

### Web Reinforcing
1. Inhibits the growth of diagonal crakcs beyond initial tensile cracking
2. Increases beam ductility. A nominal amount of web reinforcement should be included in all beams located in areas of moderate+ seismic and/or wind activity
3. The bars crossing a particular crack resist a portion of the shear force

### Flexrual transvere shear stress (NA to Shear Walls)
1. Allowable shear stress resisted by the masonry (Fvm) is calculated by equation 8-25 for special reinforced masonry shear walls and 8-26 for all others
2. The allowable shear stress is calculated using 8-23 low moments relative to shear and 8-24 for high moments relative to shear
3. Code allowable: 
    ```
    Fv = (Fvm + Fvs)yg
    ```
    where yg=0.75 for partially grouted walls and 1 for all others
4. In cantilevered beams, the shear at the face of the support should be used
5. In other beams, where no load exists between the support and d/2 from the support, the design  shear may be at the d/2 location

### Flexural in-plane wall shear stress
1. Uncracked section: 
    ```
    fv = V/(tL)
    ```
    where t = actual thickness accounting for partial grouting of vertical cells
    L = wall length
2. Cracked section: 
    ```
    fv = V/(bd)
    ```
    where d = distance along the wall
    b = thickness
3. Shear walls may or may not be load bearing
4. M/Vd becomes a factor in allowable shear loads for reinforced masonry shear walls. Lower moments loead to higher allowable shear stresses. These requirements provide ductile instead of brittle failures
5. The value of M is taken at the location V is calculated
6. Without shear reinforcing: where M/Vd < 0.25, the wall is long and deep compared to its height and behaves more like a shear element than a flexural element. There is a large amount of shear area available so higher shear stresses are allowed as a shear failure is unlikely in a deep element
    ```
    Fv <= 3sqrt(f'm)yg
    ```
7. Without shear reinforcing where M/VD is >= 1, the in-plane wall is more of a vertical flexural element than a shear element and equations similar to beam equations are used but with lower maximum allowable stresses
    ```
    Fv <= 2sqrt(f'm)yg
    ```

## Experience Based Rules of Thumb
1. Shear can be economically used to set beam depth. Some designers set beam depth as dictated by "all shear to be carried by the masonry and no shear reinforcing needed." This cuts down on labor significantly.
2. Shear calculations are critical for in-plane shear wall design.
3. Shear seldom controls out-of-plane wall design.
4. Keep beam stirrup configuration as simple as possible.

## Development Length, Lap Lengths, and Flexural Bond
1. Tension development length = 0.0002 Db Fs or 12-in minimum and 40 bar diameters minimum, which is 40 bar diameters for grade 40 steel and 48 bar diameters for grade 60 steel
2. Compression development length = same as tension development length per TMS 6.1.5.1

## Compressive Beam Reinforcement
1. Seldom used because masonry beam sections are usually large and deep; inefficient as a lot of steel is added for marginal improvements in strength. Better solutions include increasing depth, using stronger units, or using other materials
2. Previous TMS editions have indicated that reinforcement may not be used unless the member is confined. Geometric configurations to confine the steel reinforcement is often difficult.
3. Beam compressive steel used to resist flexure is designated as As', the allowable stress as Fs', and the actual stress as fs'. The adjacent masonry in compression due to flexure has a stress of f s'. The compressive reinforcement replaces the compressive masonry, but the loss of masonry area is usually negligible. The location of the compressive reinforcement is d'. A revised equation for the netural axis, kd, can be derived accounting for the compressive reinforcement.
4. DUring long term creep and shrinkage scenarios, the compression steel takes on more force than the adjacent masonry.
5. Masonry codes use the same approach to compression steel design as concrete working stress design.
6. Use compression steel when structural depth is limited by architectural requirements or where tension steel alone gives unreasonable reinforcement amount and material or geometry changes are not available solutions.