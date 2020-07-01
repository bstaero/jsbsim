# JSBSim Properties
### Initial Conditions

ic/vc-kts (read/write) Calibrated airspeed initial condition in knots
ic/ve-kts (read/write) Knots equivalent airspeed initial condition
ic/vg-kts (read/write) Ground speed initial condition in knots
ic/vt-kts (read/write) True airspeed initial condition in knots
ic/mach (read/write) Mach initial condition
ic/roc-fpm (read/write) Rate of climb initial condition in feet/minute
ic/gamma-deg (read/write) Flightpath angle initial condition in degrees
ic/alpha-deg (read/write) Angle of attack initial condition in degrees
ic/beta-deg (read/write) Angle of sideslip initial condition in degrees
ic/theta-deg (read/write) Pitch angle initial condition in degrees
ic/phi-deg (read/write) Roll angle initial condition in degrees
ic/psi-true-deg (read/write) Heading angle initial condition in degrees
ic/lat-gc-deg (read/write) Latitude initial condition in degrees
ic/long-gc-deg (read/write) Longitude initial condition in degrees
ic/h-sl-ft (read/write) Height above sea level initial condition in feet
ic/h-agl-ft (read/write) Height above ground level initial condition in feet
ic/sea-level-radius-ft (read/write) Radius of planet at sea level in feet
ic/terrain-elevation-ft (read/write) Terrain elevation above sea level in feet
ic/vg-fps (read/write) Ground speed initial condition in feet/second
ic/vt-fps (read/write) True airspeed initial condition in feet/second
ic/vw-bx-fps (read/write) Wind velocity initial condition in Body X frame in feet/second
ic/vw-by-fps (read/write) Wind velocity initial condition in Body Y frame in feet/second
ic/vw-bz-fps (read/write) Wind velocity initial condition in Body Z frame in feet/second
ic/vw-north-fps (read/write) Wind northward velocity initial condition in feet/second
ic/vw-east-fps (read/write) Wind eastward velocity initial condition in feet/second
ic/vw-down-fps (read/write) Wind downward velocity initial condition in feet/second
ic/vw-mag-fps (read/write) Wind velocity magnitude initial condition in feet/sec.
ic/vw-dir-deg (read/write) Wind direction initial condition, in degrees from north
ic/roc-fps (read/write) Rate of climb initial condition, in feet/second
ic/u-fps (read/write) Body frame x-axis velocity initial condition in feet/second
ic/v-fps (read/write) Body frame y-axis velocity initial condition in feet/second
ic/w-fps (read/write) Body frame z-axis velocity initial condition in feet/second
ic/vn-fps (read/write) Local frame x-axis (north) velocity initial condition in feet/second
ic/ve-fps (read/write) Local frame y-axis (east) velocity initial condition in feet/second
ic/vd-fps (read/write) Local frame z-axis (down) velocity initial condition in feet/second
ic/gamma-rad (read/write) Flight path angle initial condition in radians
ic/alpha-rad (read/write) Angle of attack initial condition in radians
ic/theta-rad (read/write) Pitch angle initial condition in radians
ic/beta-rad (read/write) Angle of sideslip initial condition in radians
ic/phi-rad (read/write) Roll angle initial condition in radians
ic/psi-true-rad (read/write) Heading angle initial condition in radians
ic/lat-gc-rad (read/write) Geocentric latitude initial condition in radians
ic/long-gc-rad (read/write) Longitude initial condition in radians
ic/p-rad_sec (read/write) Roll rate initial condition in radians/second
ic/q-rad_sec (read/write) Pitch rate initial condition in radians/second
ic/r-rad_sec (read/write) Yaw rate initial condition in radians/second

### Acclerations

accelerations/pdot-rad_sec2 	rad/s^2
accelerations/qdot-rad_sec2 	rad/s^2
accelerations/rdot-rad_sec2 	rad/s^2
accelerations/udot-ft_sec2 	rad/s^2
accelerations/vdot-ft_sec2 	rad/s^2
accelerations/wdot-ft_sec2 	rad/s^2
accelerations/gravity-ft_sec2 	rad/s^2
accelerations/a-pilot-x-ft_sec2 	rad/s^2
accelerations/a-pilot-y-ft_sec2 	rad/s^2
accelerations/a-pilot-z-ft_sec2 	rad/s^2
accelerations/n-pilot-x-norm
accelerations/n-pilot-y-norm
accelerations/n-pilot-z-norm
accelerations/Nz
accelerations/Ny


### Attitude

attitude/pitch-rad 	rad 	Pitch
attitude/roll-rad 	rad 	Roll
attitude/heading-true-rad 	rad 	True heading

### Flight Control Surfaces

fcs/aileron-cmd-norm 	- 	Aileron command(normalized)
fcs/elevator-cmd-norm 	- 	Elevator command(normalized)
fcs/rudder-cmd-norm 	- 	Rudder command(normalized)
fcs/flap-cmd-norm 	- 	Flap command(normalized)
fcs/speedbrake-cmd-norm 	- 	Speedbrake command(normalized)
fcs/spoiler-cmd-norm 	- 	Spoiler command(normalized)
fcs/pitch-trim-cmd-norm 	- 	Pitch trim command(normalized)
fcs/roll-trim-cmd-norm 	- 	Roll trim command(normalized)
fcs/yaw-trim-cmd-norm 	- 	Yaw trim command(normalized)

fcs/left-aileron-pos-rad 	rad 	Left aileron position
fcs/left-aileron-pos-deg 	deg 	Left aileron position
fcs/left-aileron-pos-norm 	- 	Left aileron position(normalized)
fcs/mag-left-aileron-pos-rad 	rad 	Mag. left aileron position

fcs/right-aileron-pos-rad 	rad 	Right aileron position
fcs/right-aileron-pos-deg 	deg 	Right aileron position
fcs/right-aileron-pos-norm 	- 	Right aileron position(normalized)
fcs/mag-right-aileron-pos-rad 	rad 	Mag. right aileron position

fcs/elevator-pos-rad 	rad 	Elevator position
fcs/elevator-pos-deg 	deg 	Elevator position
fcs/elevator-pos-norm 	- 	Elevator position(normalized)
fcs/mag-elevator-pos-rad 	rad 	Mag. elevator position

fcs/rudder-pos-rad 	rad 	Rudder position
fcs/rudder-pos-deg 	deg 	Rudder position
fcs/rudder-pos-norm 	- 	Rudder position(normalized)
fcs/mag-rudder-pos-rad 	rad 	Mag. rudder position

fcs/flap-pos-rad 	rad 	Flap position
fcs/flap-pos-deg 	deg 	Flap position
fcs/flap-pos-norm 	- 	Flap position(normalized)

fcs/speedbrake-pos-rad 	rad 	Speedbrake position
fcs/speedbrake-pos-deg 	deg 	Speedbrake position
fcs/speedbrake-pos-norm 	- 	Speedbrake position(normalized)
fcs/mag-speedbrake-pos-rad 	rad 	Mag. speedbrake position

fcs/spoiler-pos-rad 	rad 	Spoiler position
fcs/spoiler-pos-deg 	deg 	Spoiler position
fcs/spoiler-pos-norm 	- 	Spoiler position(normalized)
fcs/mag-spoiler-pos-rad 	rad 	Mag. spoiler position

gear/gear-pos-norm 	- 	Gear position(normalized)
gear/gear-cmd-norm 	- 	Gear command(normalized)
fcs/left-brake-cmd-norm 	- 	Left brake command(normalized)
fcs/right-brake-cmd-norm 	- 	Right brake command(normalized)
fcs/center-brake-cmd-norm 	- 	Center brake command(normalized)
fcs/steer-cmd-norm 	- 	Steer command(normalized)

gear/tailhook-pos-norm 	- 	Tailhook position(normalized)
fcs/wing-fold-pos-norm 	- 	Wing fold position(normalized)

fcs/throttle-cmd-norm 	- 	Throttle command(normalized)
fcs/throttle-pos-norm 	- 	Throttle position(normalized)
fcs/mixture-cmd-norm 	- 	Mixture command(normalized)
fcs/mixture-pos-norm 	- 	Mixture position(normalized)
fcs/advance-cmd-norm 	- 	Advance command(normalized)
fcs/advance-pos-norm 	- 	Advance position(normalized)
fcs/feather-cmd-norm 	- 	Feather command(normalized)
fcs/feather-pos-norm 	- 	Feather position(normalized)

### Position

position/h-sl-ft 	ft 	Altitude above sea level
position/h-sl-meters 	m 	Altitude above sea level
position/lat-gc-rad 	rad
position/long-gc-rad 	rad
position/lat-gc-deg 	deg
position/long-gc-deg 	deg
position/lat-geod-rad 	rad
position/lat-geod-deg 	deg
position/geod-alt-ft 	ft
position/h-agl-ft 	ft 	Altitude above ground level
position/geod-alt-km 	km
position/h-agl-km 	km
position/radius-to-vehicle-ft 	ft
position/terrain-elevation-asl-ft 	ft
position/eci-x-ft 	ft
position/eci-y-ft 	ft
position/eci-z-ft 	ft
position/ecef-x-ft 	ft
position/ecef-y-ft 	ft
position/ecef-z-ft 	ft
position/epa-rad 	rad
position/distance-from-start-lon-mt 	mt
position/distance-from-start-lat-mt 	mt
position/distance-from-start-mag-mt 	mt
position/vrp-gc-latitude_deg 	deg
position/vrp-longitude_deg 	deg
position/vrp-radius-ft 	ft

### Propulsion

/engine[0] - First engine. Replace [0] with your engine number.
/tank[0] - First fuel tank. Replace [0] with your fuel tank number.

### Shared

propulsion/set-running 	- 	Init. running
propulsion/starter_cmd 	- 	Starter command
propulsion/active_engine 	- 	Get active engine
propulsion/total-fuel-lbs 	lbs 	Total amount of fuel
propulsion/refuel 	- 	Refuel
propulsion/fuel_dump 	- 	Fuel dump
forces/fbx-prop-lbs 	lbs
forces/fby-prop-lbs 	lbs
forces/fbz-prop-lbs 	lbs
moments/l-prop-lbsft 	lbs-ft
moments/m-prop-lbsft 	lbs-ft
moments/n-prop-lbsft 	lbs-ft
propulsion/engine[0]/thrust-lbs 	lbs 	Thrust for selected engine
propulsion/tank[0]/contents-lbs 	lbs 	Fuel content in selected tank
propulsion/tat-r 	ºR 	Total temperature, isentropic flow
propulsion/tat-c 	ºC 	Total temperature, isentropic flow
propulsion/pt-lbs_sqft 	sqft 	Total pressure

### Piston engine specific

propulsion/magneto_cmd 	- 	Magnetos command
propulsion/engine[0]/power-hp 	HP 	Engine power
propulsion/engine[0]/friction-hp 	HP 	Static friction
propulsion/engine[0]/bsfc-lbs_hphr 	- 	ISFC
propulsion/engine[0]/starter-norm 	- 	Starter gain
propulsion/engine[0]/volumetric-efficiency 	- 	Volumetric efficiency
propulsion/engine[0]/map-pa 	pa 	Manifold absolute pressure
propulsion/engine[0]/map-inhg 	inHg 	Manifold absolute pressure
propulsion/engine[0]/air-intake-impedance-factor 	- 	Z airbox
propulsion/engine[0]/ram-air-factor 	- 	Ram air factor
propulsion/engine[0]/cooling-factor 	- 	Cooling factor
propulsion/engine[0]/boost-speed 	- 	Boost speed
propulsion/engine[0]/cht-degF 	ºF 	Cylinder head temperature
propulsion/engine[0]/oil-temperature-degF 	ºF 	Oil temperature
propulsion/engine[0]/oil-pressure-psi 	psi 	Oil pressure
propulsion/engine[0]/egt-degF 	ºF 	Exhaust gas temperature

### Propeller specific

propulsion/engine[0]/engine-rpm 	RPM 	Get engine RPM
propulsion/engine[0]/advance-ratio 	J 	Advance ratio
propulsion/engine[0]/blade-angle 	- 	Blade angle
propulsion/engine[0]/thrust-coefficient 	- 	Get thrust coefficient
propulsion/engine[0]/propeller-rpm 	RPM 	Get propeller RPM
propulsion/engine[0]/helical-tip-Mach 	- 	Get helical tip Mach
propulsion/engine[0]/constant-speed-mode 	- 	Get constant speed
propulsion/engine[0]/prop-induced-velocity_fps 	fps 	Get induced velocity

### Turbine & Turboprop engine specific

propulsion/cutoff_cmd 	- 	Cutoff command
propulsion/engine[0]/n1 	- 	Nozzle 1
propulsion/engine[0]/n2 	- 	Nozzle 2

### Velocities
velocities/h-dot-fps 	fps
velocities/v-north-fps 	fps
velocities/v-east-fps 	fps
velocities/v-down-fps 	fps 	Vertical speed
velocities/u-fps 	fps
velocities/v-fps 	fps
velocities/w-fps 	fps
velocities/u-aero-fps 	fps
velocities/v-aero-fps 	fps
velocities/w-aero-fps 	fps
velocities/p-rad_sec 	rad/s 	Roll speed
velocities/q-rad_sec 	rad/s 	Pitch speed
velocities/r-rad_sec 	rad/s 	Yaw speed
velocities/p-aero-rad_sec 	rad/s
velocities/q-aero-rad_sec 	rad/s
velocities/r-aero-rad_sec 	rad/s
velocities/pi-rad_sec 	rad/s
velocities/qi-rad_sec 	rad/s
velocities/ri-rad_sec 	rad/s
velocities/eci-x-fps 	fps
velocities/eci-y-fps 	fps
velocities/eci-z-fps 	fps
velocities/eci-velocity-mag-fps 	fps
velocities/ned-velocity-mag-fps 	fps
velocities/vc-fps 	fps 	Airspeed
velocities/vc-kts 	kts 	Airspeed
velocities/ve-fps 	fps
velocities/ve-kts 	kts
velocities/vtrue-fps 	fps
velocities/vtrue-kts 	kts
velocities/machU
velocities/phidot-rad_sec 	rad/s
velocities/thetadot-rad_sec 	rad/s
velocities/psidot-rad_sec 	rad/s
velocities/vt-fps 	fps
velocities/mach
velocities/vg-fps 	fps
velocities/vg-fps 	fps

### Atmosphere

atmosphere/T-R The current modeled temperature in degrees Rankine.
atmosphere/rho-slugs_ft3
atmosphere/P-psf
atmosphere/a-fps
atmosphere/T-sl-R
atmosphere/rho-sl-slugs_ft3
atmosphere/P-sl-psf
atmosphere/a-sl-fps
atmosphere/theta
atmosphere/sigma
atmosphere/delta
atmosphere/a-ratio


