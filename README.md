# Musical Geometry
## Chapter 1: The Five Components of Tonality
### The Five Features

1. Conjunt Melodic Motion
2. Acoustic Consonance
3. Harmonic Consistency 
4. Limited Macroharmony
5. Centricity

### The Four Claims
1. Harmony and counterpoint constrain one another
2. Scale, macroharmony, and centricity are independent
3. Modulation involves voice leading
4. Music can be understood geometrically 

## Chapter 2: Harmony and Voice Leading
### Pitch Spaces
**Linear Pitch Space**: Octave is important   
**Circular Pitch-Class Space**: Octave is *not* important

### Geometrical Analogies
Translation = Transposition  
Inversion = Reflection  
**Registral Inversion** = C4-E4-G4 --> E4-G4-C5
**Pitch-space-inversion** = C4-E4-G4 --> G4-Eb4-C4 

### Musical Objects
*Symmetry operations will leave the "essential identity" unchanged* 

| Operation         | Allowable Action           
| -------------     |:-------------:| 
| Octave            | Move *any* note into a new octave | 
| Permutation       | Reoder the object (*rotate*)      |   
| Transposition     | Move *all* of its notes in the same                             direction by the same amount      |    
| Inversion         | Turn the object "upside down"     |       
| Cardinality Change| Add a new voice duplicating one of                              the notes in the new object       |

**Chord**: octave shifts, permutations, and note-dulication  
**Multiset**: octave shifts, and permutation  
**Tone Row**: shift octaves, and note-duplication  

| Term              | Symmetry           
| -------------     |:-------------:| 
| Chord                                  |**OPC**   | 
| Transpositional Set Class              |**OPTC**  | 
| Set Class                              |**OPTIC** |
| Multiset of pitch classes              |**OP**    |
| Chord (of pitches)                     |**PC**    |
| Tone Row (ordered set of pitch classes)|**OC**    |

____
### Voice Leading and Chord Progressions
*With chord-progressions one can apply the symmetry operations to the musical objects individually or uniformally*  

**Chord Progression**: A series of *un-ordered* musical objects 
**Voice Leading**: A series of *ordered* musical objects

| Term              | Symmetry           
| -------------     |:-------------:| 
| Voice leading in pitch space             | uniform  **P** | 
| Voice leading in pitch-class space       | uniform **OP** |   
| Pitch-space chord progression            | individual **PC** |
| Chord progression                        | individual **OPC**|
| Path in pitch-class space                | uniform **O**     |

### Comparing Voice Leading
#### Individual and Uniform Transposition

**Uniformly T(transpositionally)-related**: (C, E, G) => (C, F, A) && (G, B, D) => (G, C, E)  
**Individually T(transpositionally)-related**: (C, E, G) => (C, F, A) && (G, B, D) => (F#, B, D#)  
*Each maps the root of the first chord to the fifth of the second, the third of the first chord to the root of the second, and the fifth of the first chord to the third of the second.*
#### Inidivudal and Uniform Inversion
**Uniformly I(inversionally)-related**: (G, E, G)-> (C, F, A) && (G, Eb, C) => (G, D, Bb)  
**Individually I(inversionally)-related**: (C, E, G) => (C, F, A) && (G, Eb, C) => (G#, D#, B)  
*The two voice leadings are miror images of each other: the first moves one voice by zero semitones, one voice up by one semitone, and one voice up by two semitones; the second moves one voice by zero semitones, one voice down by one semitone, and one voice down by two desmitones. Succesive voice leading is similar even though they are not related by excact transposition*  

### Voice-Leading Size
*Precise measurement is not practical: we'll define what is reasonable*  
1. It should depend only on *how far* the individual voices move, with larger motion leading to large voice leadings; 
2. it should judge voice leadings with *voice crossings* to be larger ( or at the very least, no smaller)  
*Generally: smaller amounts of motion in more voices is preferred as apposed to larger amounts of motion in fewer voices.*

**Implications**   
* The more evenly a chord divides the octave, the smaller the voice leadings to irs various transpositions
* E and Ab major triads can be linked to the C major traid by smaller voice leadings than any other major triads

## Near Identity 
**Chord *Closeness***: linked by efficient voice leading
**Chord Type *Closeness***: relatively small voice leading between their transpositions. 

*The diminished triad is closer to the minor triad than to the chromatic cluster, since there is a very small voice lading taking C diminished to C minor, but no similarly small voice leading connecting any diminished triad to any chromatic cluser.*

**Nearly transpositionally related**: C dim --> C minor (which is in turn transpositionally related to F minor)
**Nearly inversionally related**: {C, Db, G} --> { Eb, G, A} (meaning {C, Db, G} is near {C, D, F#} which is inversionally related to {Eb, G, A})