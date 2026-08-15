# Slim-Jim-Antenna
Homebrew 2m VHF Slim Jim Antenna (4mm Solid Copper)

A 2-meter 144–146 MHz Slim Jim antenna built from 4mm insulated solid copper electrical wire. Designed specifically for lowangle omnidirectional radiation, making it ideal for contacting local VHF repeaters, long distance ground stations, and tracking LEO low earth orbit satellites and the ISS International space station downlink.


Specs

Frequency range      -       144 to 146 MHz
Antenna type         -       Parallel wire dipole of Slim Jim with J Pole configs
Polarization         -       Vertical
Impedance            -       50 $\Omega$ nominal
Radiation pattern    -       Omnidirectional with low elevation angle
Radiator material    -       4mm insulated solid copper wire
Feedline             -       75 $\Omega$ / 50 $\Omega$ coaxil (with ugly balun)


Antenna Dimensions

All measurements account for the approx 0.95 velocity factor of insulated 4mm copper wire.
Total Overall Height: 142 cm
Parallel spacing: 2.5 cm   *with non conducting material
Long Element (Left Side): 142 cm continuous unbroken wire
Short Element (Right Side):
   -Bottom Matching Stub: 47 cm
   -Gaping(Slot): 2.5 cm    *make it an open circuit)\
   -Top Radiator Section: 92.5 cm
Feed Point Height and Coax connection: 10cm measured straight up from the bottom fold base of both elements, conecting coax centre copper and braided wires to each one.
Coax Connections (above and):
  -Center copper conductor: Soldered to the continuous (Left) element.
  -Shield Braid: Soldered to the (Right) element.


Build notes & construction

Skeleton(mechanical) support: Mounted along a non-conductive stand (PVC casing/pipe, wood, etc) to prevent flex and preserve element spacing.
RF choke (ugly balun): Coiled 4 or 5 turns of coax with 10 cm diametre directly below the feed point.
Weather proofing: Solder all the joints and taped with electrical insulation tape. Gap ends also left insulated to prevent water entering during rain.


Applications
ISS (frequency 145.800 MHz): Good low horizon reception for voice and APRS packet downlinks.
Local VHF repeaters: Signals travel through terrain barriers over long distances(to an extent) due to suppressed high angle radiation.
Handheld radio comms: Matches directly to sdr's and standard VHF transceivers via SMA to BNC/SO239 adapters.
