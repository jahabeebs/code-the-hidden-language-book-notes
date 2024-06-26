<pre>
Chapter 1: Best Friends
    Some strategies for non-verbal communication
        Bad: flashlight to draw letters
        Bad: blinks of light to communicate a specific letter (1 for A, etc.)
        Good: morse code

Chapter 2: Codes and Combinations
    Morse code introduction
        Invented 1837 and developed by others
        Goes hand in hand with telegraph invention
            Telegraph has similar hardware to a computer
        Number of codes = 2 ^ number of dots and dashes
            For example, 1 dot or dash can produce 2^1 different codes
        Morse code is considered binary because consists of dot & dash

Chapter 3: Braille and Binary Codes
    Creation of braille
        Charles Barbier, French army captain devised idea of "night writing"
            Raised dots on paper for sailors to pass notes in quiet
        Louis Braille liked concept of braille because it was easy to write
    Anatomy of braille
        Every symbol encoded in 2x3 cell and dots numbered 1-6
        Dots are binary--either raised or flat
        Can represent 64 unique codes
    Code errors
        Error when code is written: encoding error
        Error when code is read: decoding error
        Error when code is delivered: transmission error
    Precedence/shift codes & escape codes
        Shift codes: alter meaning of subsequent codes until shift ends
            Like holding down shift on keyboard
        Escape codes: alter only the following character

Chapter 4: Anatomy of a Flashlight
    Incandescent lightbulb
        Precursor to LED
        Filament made of tungsten that glows when electricity on
        Bulb filled w/inert gas to prevent tungsten from burning up
    Circuits are a circle
        Batteries must be connected in parallel rather than in series
        Combined voltage of 1.5 volts if each battery is 1.5 volts
        Atom w/electrons in outer shell are conducive to carrying electricity and called conductors
            Best conductors are copper, silver, and gold
            Opposite of conductance is resistance (resistors)
            Very high resistance is an insulator
            Longer wire -> higher resistance
            Thicker wire -> lower resistance (more electrons can move through wire)
    Electricity history
        Electron theory explains electricity as movement of electrons
        Electron & electricity derive from ancient Greek (elektron) which means amber
            Greeks generated static electricity by rubbing amber and wool
        Imbalance of protons and electrons will attempt to correct itself
        Electrons in a circuit are more orderly than in a lightning bolt because of clear passage
        Batteries have cathode (+) and anode (-) and converts chemical to electrical energy
    Voltage
        Voltage is potential for doing work
        Exists whether or not a battery is hooked up
    Current
        Related to # of electrons zipping around circuit and measured in amperes/amps
    Water and pipes analogy
        Current is similar to amount of water and voltage is similar to water pressure
        Resistance similar to width of pipe
    Ohm's law
        I = E/R
        I = current in amperes
        E = voltage (electromotive force)
        R = resistance
    Battery diagrams
        A squiggly line represents resistor--not a very low or high resistance
        Incandescent bulb has resistance of 4 ohms
    Watt 
        P = E * I
        P = power
    Switches
        Either electricity on or off--just like binary
        Closed switch = electricity flowing

Chapter 5: Communicating Around Corners
    Two flashlights, two batteries, three wires = bidirectional telegraph system
    Connection between two circuits called a common
    Can use the Earth instead of a common
        Earth is huge so can conduct well
        Need something with substantial contact to Earth like a buried large copper pole
        Called a "ground" in America
        Would only need wire between house and friend's house if using a high-voltage battery & bulb
        Two-way Morse code system can be constructed w/just two wires by using copper poles 
    Overcoming resistance
        Thickness of wire measured in American Wire Gauge (AWG)
        Smaller AWG = thicker wire = less resistance

Chapter 6: Logic with Switches
    Basis of Aristotle's logic was syllogism
        Two premises assumed to be correct and a conclusion is deduced
    George Boole
        Believed human brain uses logic so if we could represent logic we would know how the brain works
        Invented boolean algebra in which letters are operands and are combined with operators (+, x)
    Traditional algebra properties
        Addition and multiplication are commutative (we can switch around symbols on each side of operators)
        Subtraction and division are not commutative
        Addition and multiplication are associative
            A + (B + C) = (A + B) + C
        Multiplication is distributive over addition 
    Boole divorced algebra from concept of numbers
        Operands refer to classes not numbers
            Class is a group of things, similar to what a set is now considered
            Ex: M refers to class of male cats and F refers to class of female cats
        + symbol means union of two classes (M + F) = class of all cats that are male or female
        x symbol means intersection of two classes (M x F) = class of all cats that are BOTH male and female
        Commutative, associative, and distributive rules apply for Boolean algebra
        The symbol 1 means "the universe" or everything we're discussing
            M + F = 1 means the union of male and female cats is the class of all cats
            1 - M means the class of all cats except male cats
            1 - M = F means the universe excluding all male cats is same as the class of female cats
        The symbol 0 means an empty class, like when take an intersection of two exclusive classes
            F x M = 0 because there are no cats that are both male and female
    The roles of "or" and "and"
        + symbol can mean OR
        x symbol can mean AND
        1 - means NOT
    Circuitry and boolean logic
        Circuits can represent "and" and "or" via switches
        Switches connected in parallel don't both have to be closed for the circuit to work (represents OR)
        
Chapter 7: Telegraphs and Relays
    Morse (born 1791) relied on electromagnetism for long-distance communication
        An iron bar wrapped with thin, insulated, electrified wire will create a magnet
        Electromagnet is foundation of telegraph
            Turning switch on and off at one end causes electromagnet to do something at other end
    Telegraph was demoed publicly in 1843
        Telegraph used by holding and handle and tapping it up and down
        Short tap produces Morse code dot and long tap produces morse code dash
    Telegraph advancements
        Telegraph sounder used to create click clack noises
            Telegraph key was pressed, electromagnet pulled bar down to make a click noise
                Releasing key made a clack noise
            Fast click-clack = dot; slower click-clack was dash
    Repeater or relay
        Similar to a sounder because current is used to power electromagnet that pulls a lever
            Different because lever is used as part of a switch that connects battery to outgoing wire
        Amplifies weak incoming current to create stronger outgoing current

Chapter 8: Relays and Gates
    Logic gates--embody melding of math and hardware 
        Computer is a synthesis of Boolean algebra & electricity
    Circuit vs. network
        Current must pass through all elements in circuit but not necessarily in network
    Networks
        Panel of switches constitutes an input device
        Output device can be a lightbulb for example
    Relays can be connected in series and in parallel as logic gates to perform tasks
        Relays unlike switches can be switched on and off by other relays
        When electromagnet pulls metal contact the relay is triggered
        If current flows through input then electromagnet triggered and output has voltage
    Output of one relay can be connected to input of another relay
        Relays are considered cascaded
        Connecting relays is key to logic gates
    Relays can be connected to form an "AND gate"
        AND gate can connect to another AND gate
        Two relays wired in parallel considered OR gate
    Diagrams in book are double-throw relays
        Pivoting metal bar touches one contact and when electromagnet touches it then it hits another
        Upper contact called normally closed
        Lower contact called normally open
    Single throw relay considered an inverter
        Inverts 0 (no voltage) to 1 (voltage) and vice versa
        Represents Boolean NOT operator
    Rules on connecting gates and inverters
        Output of one gate or inverter can be input to 1+ other gates (or inverters)
        Cannot connect outputs of two or more gates (or inverters) to one another
    Other types of logic gates
        NOT OR/NOR logic gate
            Both switches closed then lightbulb off
            Top or bottom switch closed then light is off
        NOT AND/NAND logic gate
            Lightbulb goes off when both switches closed
        Buffer
            Simple relay that doesn't change input
            Output same as input
            Sometimes one output must serve as many inputs
                Called fan out
                Buffers can boost power at each output
            Can slightly delay a signal too
    NAND and NOR can create all other logic gates
        
Chapter 9: Our Ten Digits
    Humans use base-ten or decimal system because we have ten fingers
        Roman numerals invented to make it so single lines didn't have to represent big numbers
        Existing roman numerals are I (1), V (5), X (10), L (50), C (100), D (500), M (1000)
    Our current number system is Hindu-Arabic/Indo-Arabic
        Indian origin but brought to Europe by Arab mathematicians
        Differs in three ways from previous systems
            Hindu-Arabic system is positional
            No special symbol for ten
            Has zero

Chapter 10: Alternative 10s
    Decimal/base ten system
        In an octal system numbers are 0, 1, 2, 3, 4, 5, 6, 7, then 10 
            Because no special symbol for 10 in base ten system
    Converting quaternary system to base ten system
        31232 to base ten
            3 * 4^4 + 1 * 4 ^ 3, etc. = 878 in decimal
    Converting binary to decimal
        10010110
            1 * 128 + 0 * 64 + 0 * 32, etc.
        Converting decimal to binary is similar but with division
            Have to divide until get a quotient and remainder
            Keep moving remainder to next box until it can be divided
    In 1947 American mathematician Tukey wanted to replace "binary digit"
        Decided on bit

Chapter 11: Bit by Bit by Bit
    A bit is the basic building block of information
        Information represents choice among 2+ possibilities
        Any info that can be reduced to choice among 2+ possibilities can be represented with bits
        # of possible codes equal to 2 to the power of number of bits
    Codes -> bits
        2^7 = 128 is same as log2(128) = 7
    Binary powers UPC codes, QR codes

Chapter 12: Bytes and Hexadecimal
    What is a word?
        Group of certain # of bits
        Computer data moves in groups of 1 or more words
    Anatomy of a word
        Early computers used word lengths that were multiples of 6 bits
            Very easy to represent w/octal numbers: 0, 1, 2, 3, 4, 5, 6, 7 (each 3 bits)
    Start of the byte
        Originated at IBM around 1956
        Came to mean group of 8 bits (00000000 to 11111111, or 0 through 255)
        Bytes also ideal for shades bc human eye can only differentiate 256 shades of gray
        Half a byte (4 bits) considered a nibble
    The hexadecimal base 16 system 
        0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F, 10, 11, 12...
        Each byte is 8 bits, or two hexadecimal digits ranging from 00 to FF
        To denote hexadecimal add a lowercase h following a number
            10h is 16, 18h is 24, 20h is 32, etc.
    `   Common to express big binary numbers in groups of 4 bc of hexadecimal
    HTML and colors
        #E74536 = red value of E7h, green value of 45h, blue value of 36h
        Positions of each digit correspond to powers of 16
            65,536 & 4,096 & 256 & 16 & 1
            9A48Ch = 9 * 16^4 + A * 16^3...

Chapter 13: From ASCII to Unicode
    Codes vs. binary
        Morse code is variable bit-length code because characters require different # of bits
        Braille is strictly a 6-bit code but uses shift codes
    Shift codes
        Show up in early binary--they change the meaning of the following characters
            Called Baudot code and was used for sending and receiving telegrams
    Baudot code
        Transmission speeds of binary data can be called baud rates
        Baudot code often used in teletypewriter--similar to typewriter but w/30 keys and spacebar
        Baudot code is 5 bits so only 32 codes
    ASCII code (7 bits) replaced Baudot code
        American Standard Code for Information Interchange
        Most important standard in computer industry--affects all text on a computer
        Includes the characters of a keyboard basically (including uppercase)
        Add 20h to code for an uppercase letter to convert to lowercase
        ASCII has 95 graphic characters with visual representation
        ASCII has 33 control characters with no visual representation but w/functions
            Most are for typewriters but also includes tab, backspace, etc.
        Extended ASCII character set contains 256 characters rather than just 128
    Files are collections of bytes identified by a name
        ASCII character files have txt (plain text) filename extension
        Fancy text like italics is formatted text or rich text
        ASCII technically 7-bit code but stored as 8-bit values because of computer architecture
    HTML is most popular rich-text format
        Adds formatting to plain text by using markup or tags
        Uses normal ASCII characters for markup so technically is also a plain-text file
    ASCII compatibility issues
        Multiple incompatible double-byte character sets
        Some characters (like normal ASCII characters) are represented by 1-byte codes
            Thousands of ideographs are represented by 2-byte codes
    Unicode (16-bit code) developed as alternative to ASCII
        First 128 characters are same as ASCII characters
        Standard way to indicate is prefacing value with capital U and a plus sign
            U+0041 is character 'A'
    Big-endian vs little-endian machines
        Some computers read most significant byte (big end) first 
        Other computers read least significant byte first
        Unicode defines character called byte order mark (U+FEFF) to specify order
    Unicode had to expand beyond 16 bits to include more symbols and extinct scripts
        Unicode now a 21-bit code with values through U+10FFFF
    Several methods defined for storing and transmitting Unicode text
        Called Unicode transformation formats (UTFs)
        Most straightforward UTF is UTF-32
            All Unicode characters defined as 32-bit values
            Downside is uses a lot of space (11 bits wasted)
        UTF-16 defines characters w/2 bytes
            Characters above U+FFFF are defined w/4 bytes
        Most important UTF is UTF-8 which is in 97% of webpages
            Notepad and TextEdit save files in UTF-8 by default
            Biggest advantage is it's backward compatible with ASCII
            Identifying bytes when decoded
                Byte begins w/0: 7-bit ASCII code
                Byte begins w/10: part of sequence of bytes representing multi-byte character code
                Bytes begins w/at least two 1 bits: first byte of multibyte character code

Chapter 14: Adding with Logic Gates
    Addition is basically the only thing computers do
    Binary addition table is simple
        + 0 1
        0 00 01
        1 01 10
        Adding pair of binary numbers results in two bits, called the sum bit and the carry bit
    Binary addition table can be divided into two tables, first for sum bit and second for carry bit
        sum 0 1
        0 0 1
        1 1 0
        carry 0 1
        0 0 0
        1 0 1
    If we want to add binary #'s up to 8 bits long we need two rows of eight switches and nine bulbs
    Exclusive OR (XOR) gate
        Combination of NAND, AND, and OR gates bc XOR represents when both NAND & OR both yield 1
        Example of encapsulation--wrapping the details for simplicity
        Can represent XOR gate with a box called a half adder
            Sometimes box like this called a black box or a clear box
        Two half adders can be combined to make a full adder
    For adding binary #'s up to 8 bits long we can use eight full adders to simplify
        First column doesn't include carry bit which is why carry input to full adder is connected to ground
        Carry output from first full adder is an input to second full adder
    Can represent 8-bit adder w/double-line arrows w/an 8 to represent 8 separate signals
        These are 1-byte data paths
    Easy to cascade 8-bit adders to add two 16-bit numbers instead
        Two 16-bit input values separated into low byte and high byte
            Carry out of the adder on right is connected to carry in of adder on left

Chapter 15: Is This for Real?
    Computers don't add numbers like above anymore
        Computers today no longer made from relays
    Electromechanical computers were next generation
        Relay-based computers, the first working digital computers
        George Stibitz coined the term digital to distinguish them from analogy computers which were already in use
    Computer used to refer to a person who calculated numbers for hire
        Charles Babbage had an idea for a machine that could calculate numbers for these computers
            Never finished it
    Ada Lovelace translated an article about Babbage's machine and added sample set of instructions for it
        Ada was the first person who published a computer program though Babbage was the first programmer
    Vacuum tubes were being used as relay replacement by the 1940s
        Expensive, required a lot of power, and generated a lot of heat
        Tubes were much faster than relay
    Two physicists at Bell Labs wired a new type of amplifier constructed from germanium + gold
        The idea is that amplifiers could use semiconductors instead of vacuum tubes 
        The first transistor, which some have called the most important invention of the 20th century
    Semiconductors can be made into amplifiers by sandwiching P-type semiconductor between two N-type semiconductors (NPN transistor)
        Three pieces knows as the collector, the base, and the emitter
    In 1954 the first pocket radios used transistors made by Texas Instruments
    Texas Instrument employee discovered multiple transistors and other electronic components could be placed on a single piece of silicon
        Integrated circuit (IC) was born (aka the chip)
    Integrated circuits manufactured by layering thin wafers of silicon precisely doped and etched
        Space program and arms race in 1960s fueled early IC market
        Hearing aid was the first commercial product to use ICs
    Moore's Law predicted doubling of transistors on a chip every 18 months
        Has mostly been true
    Summary of evolution of computers
        Relay-based -> vacuum tube -> transistor -> integrated circuit

Chapter 16: Subtraction
    Nines' complement can be used for subtraction because it doesn't require a borrow
        Example: 1000 - 176 + 253 - 1000 can be rewritten as 999 - 176 + 253 + 1 - 1000
    Decimal number subtracted from string of nines is called nines' complement
    When subtracting smaller number from larger number means having to invert all bits to get result
        Called ones' complement
        There's a better way
    If result is 9 bits for an 8-bit adder, the 9th bit is an overflow
        Major addition we need to make is circuitry that calculates ones' complement of an 8-bit number
        If invert signal is 0 then output is same as input
        If invert signal is 1 then output is inverted
    Subtract switch that comes from add/subtract switch
        Signal is 0 if addition is selected and 1 if subtraction is selected
        For an addition the invert signal is 0 and the Ones' complement circuit has no effect
        For a subtraction you add 1 to result of addition by setting Carry In input of adder to 1
            Also B inputs are inverted by Ones Complement circuit before entering adder
    Negative numbers in binary are represented in two's complement
        Every 8-bit number that begins with a 1 will represent a negative number
            Leftmost bit is known as the sign bit
        Similar system is ten's complement notation
            For example to convert -255 in ten's complement subtract it from 999 and add 1 to get 745
    Have to add some additional gates to detect overflow
        AND gate detects overflow condition for adding two negative numbers (can't fit in 8 bits)
        NOR gate detects overflow for positive number
    Signed vs. unsigned binary numbers
        8-bit binary number could range from 0 to 255, called unsigned bc always positve
        8-bit binary number could range from -128 to 127, called signed bc can be positive or negative
    An integer is a number that can be positive or negative with no fractional parts
    8-bit integers often inadequate for many jobs so programmers use 16, 32, or 64-bit integers

Chapter 17: Feedback and Flip-Flops
    Oscillator: circuit that runs by itself--no human to open or close a switch
        All computers have some kind of oscillator that makes things move synchronously
        Sometimes referred to as a clock because counting its oscillations can kind of tell time
    One cycle of oscillator is interval during which output changes and comes back to where it started
        Time required for one cycle is called the period
        Frequency of oscillator is 1 divided by period
            Example: 1 / 0.02 = 50 cycles per second
            Now hertz is used rather than cycles per second
    Type of feedback is when an output circles back to become an input
    In an oscillator can close either top switch or buttom but not both at same time
    Flip-flop circuit
        Circuit with two stable states when both switches open
        Sometimes when both switches open, light stays on but sometimes it's o
        Flip-flop retains information--it's very much like a seesaw
        Two NOR gates is an R-S or Reset-Set flip-flop
    Function/logic/truth table shows outputs that result from combo of inputs
        Includes Q, Q bar (outputs), R, S (inputs)
    Level-triggered D-type flip-flop / level-triggered D-type latch / 1 bit memory
        D stands for data
        Level-triggered means flip-flop saves value of data input when clock input is at particular level (1 in this case)
    Positive transition/edge
        When clock input goes from 0 to 1
        Transition from 1 to 0 is a negative transition/edge
    Frequency divider
        When Q bar output is routed back to the data input of a flip-flop
    Ripple counter
        Output of each flip-flop becomes the clock input of the next flip-flop
        More sophisticated counters are synchronous
        Allows for counting of binary numbers -- more flip-flops = higher count
        When total reaches 11111111 (255 in decimal) it goes back to 00000000
            Sometimes know as rollover or wraparound
    This chapter had examples of integrated circuits in family known as TTL (transistor-transistor logic)
        7474 chip is a dual D-type positive-edge-triggered flip-flop with preset and clear
        First step in constructing memory

Chapter 18: Let's Build a Clock!
    Basic clock format is XX:XX:XX (hours:minutes:seconds)
        Can represent each digit in binary
            This is called binary-coded decimal or BCD
            Each digit of decimal number encoded as four-digit binary number
            Not used much in computers because it complicates arithmetic
    Using XOR gates adding switches to set time can become simple
    Cold cathode display: glass tube filled with mostly neon
        Inside are overlapping wires shaped into numbers connected to pins at the bottom
        When voltage is applied to a pin the neon surrounding the number glows
        Burroughs Corporation introduced the display and called it a Nixie tube
        Special circuits called drivers for Nixie tubes are available to supply necessary current
    Multiplexing allows decoding circuitry to be shared among multiple digits
        This prevents needing decoding circuitry for every digit needed to display
        Inputs to decoder can be shifted among different sources and outputs of decoder goes to all displays simultaneously
    Dot matrix is another approach to displaying numbers and letters
        Collection fo round lights arranged horizontally and vertically in a grid
        Made up of 35 LEDs (light-emitting diodes) which allow electrical current to flow in one direction
    Diode matrix is a collection of diodes arranged in a grid
        Considered to be a type of memory
        Cannot be changed without rewiring diodes so it's considered read-only memory or ROM

Chapter 19: An Assemblage of Memory
    Even telegraph relays can store information
        When assembled into flip-flops and logic gates it can store 1 bit
    Latch is a type of flip-flop because it latches onto data
        But we can call it memory
    Creating 1 byte of memory
        Wire together 8 bits of memory
        Connect the eight write signals
        Can be drawn as a single box
    3-to-8 decoder
        Rather than manipulate eight separate write signals can have one
        Can use decoder to govern which flip-flop it controls
    8-to-1-selector
        Effectively selects one of the eight data out signals from the flip-flops
    Writing to memory
        Set three Address (Select) signals to 010 -> set Data In to 0 or 1 -> set Write to 1 and then 0
        Value of Data is said to be stored in memory at address 010
    Reading from memory
        Set three Address signals to 010 again and see that Data Out is whatever you set Data In to
    Read/write memory
        Configuration of flip-flops, decoder, and selector
        More commonly known as random access memory, or RAM
    Particular configuration of RAM often called RAM array
        RAM array that store 256 bytes is like post office with 256 post office boxes
            Each box has a different 1-byte value
    One bit of memory knows as memory cell
    Tri-state buffer
        Can have one of three outputs: ground (logical 0), voltage (logical 1), or nothing
        Allows us to break rule prohibiting connecting outputs of logic gates
        Outputs of multiple tri-state buffers can connect without creating short circuit
    Kilobtye (KB) is 1024 bytes (2^10)  
        Problem is that metric system is based on powers of 10 and binary powers of 2
        1024 KB = 1 MB
        1024 MB = 1 GB
        1024 GB = 1 TB
    Flip-flops memory was static RAM but by 1980 dynamic RAM/DRAM was taking over
        DRAM requires only one transistor and one capacitor for each memory cell
            Capacitor contains two separated electrical conductors
            Capacitor can store electric charge but not indefinitely
            DRAM works by having capacitor charges refreshed thousands of times per second
        Both static and dynamic RAM are volatile memory

Chapter 20: Automatic Arithmetic
    An accumulator is a latch used to accumulate a running total of numbers
        An accumulator doesn't just accumulate
        Often acts as a latch that holds first one number and then that number combined with another
        Problem is when a mistake is made and need to redo a calculation
    Adding without a calculator
        First enter 8 bytes into RAM array using control panel
        Must connect RAM array to accumulating adder circuit (adder, latch, ram)
        Need control signals
            Clock input for counter, Clock input for latch, Write input for RAM
            Most complex part of a circuit like this
    When adding bytes some computers store from high to low and others low to high
        These methods are big-endian and little-endian
    Big vs little endian
        For purposes of addition you'd want to start with least significant byte
            So little-endian best for this
    Instruction does or operation codes or op codes 
        Instruct machine reading memory what to do -- like addition or subtraction
        Contents of memory can now be differentiated as code and data
    Triple-byte accumulator distinguishes hardware vs software
        Hardware is circuitry 
        Software is codes and data stored in memory
        Codes and numbers are stored in flip-flops
        Bits become signals that integrate with hardware
    Both hardware and software are electrical signals interacting with logic gates
    Microprocessor invented by 1980s
        Could access 64kb of memory and interpret 256 different opcodes
        Mostly designed for embedded systems
        Intel 8080 was first microprocessor used in home computer

Chapter 21: The Arithmetic Logic Unit
    Modern computer can be divided into three categories
        Memory, central processing unit or CPU, input and output devices, often called peripherals
    Peripherals can be visible or hidden
        Some examples are video display, keyboard, mouse, printer
        Less obvious I/O devices are circuits to play sound and music, circuits to pick up GPS
    CPU is considered the heart/soul/brain of the computer
        Similar to Triple-Byte Accumulator but generalized to respond to many codes
    Higher bit CPUs are not more capable of different types of processing
        They perform same tasks faster
    Computer program is basically a sequence of instructions in memory
        Specifically a machine code program when stored as opcodes and data
    Arithmetic logic unit (ALU) is most fundamental part of CPU
        Part of the CPU that adds and subtracts and does other tasks
        Four major operations it must be capable of for our purposes
            Add, add with carry, subtract, subtract with borrow
        If want to convert uppercase to lowercase can use bitwise OR operation
            Need to use an AND operation to convert to uppercase
        Another useful bitwise operation is exclusive OR, or XOR 
            Useful for addition
        Immediate instructions use the next byte following the operation code
            Compare operation evaluates result of operation
        Compare operation is same as subtract operation but result isn't saved anywhere
            Carry flag is saved
            Also need to know if result of operation was zero which requires a zero flag
            Sign flag needed to know if most significant bit of result is 1
        There are other flags like the parity flag and auxiliary carry flag

Chapter 22: Registers and Busses
    Bytes are moved from memory into the CPU and into the ALU
        Bytes are moved from the ALU eventually into memory
    Bytes are stored in latches while moved within the CPU
        Like the latches in Chapter 20--four 8-bitch latches, one for opcode and 3 for data bytes
    Latches called registers are 8-bit latches directly controlled by CPU instructions
        One of these latches is called the accumulator
            Always stores first of two inputs and output of ALU is always stored back in accumulator
            From accumulator output of ALU can be moved to other register or stored in memory
    Use of registers H and L in our example to form a 16-bit memory address is called indirect addressing
    If all opcodes supported by an 8-bit processor are 1 byte in length then there can be 256 opcodes
        Core arithmetical and logical functions supported by the CPU
    Assembly language instructions refer to process of assembling a computer program
        "Code to add the content of register E to the accumulator" becomes "ADD E"
        "Perform an exclusive OR operation between the accumulator and memory byte at [HL]" becomes "XRA M"
        STA means store accumulator
        LDA means load accumulator
        HLT corresponds to opcode 76h which halts the CPU
        Move instructions are abbreviated with 8080 mnemonic MOV
            For example the code 69h is MOV L,C
                Destination register appears first and source register is second
                Means move byte in register C to register 
    One way to design a CPU is to decide what instructions CPU should implement then decide on circuitry
    Register array allows CPU to store bytes in seven latches and retrieve bytes based on 3-bit codes
        8-bit values going into array can come from memory, other registers, or ALU
        8-bit values coming out of array can go to memory, other registers, or ALU
    Connection between all the inputs and outputs is called a data bus
        Data path that is common the inputs and outputs of all the components
        Only for 8-bit data; for 16-bit data we need an address bus
    Address used to access memory can come from different sources
        Program counter: 16-bit value that accesses instructions (starts at 0000h and increases until HLT)
        2 bytes following the STA or LDA operation codes which together form 16-bit address
        H and L registers form a 16-bit address; when used this way HL is called a register pair
    16-bit address bus is primarily for providing an address to the RAM
        Must also be capable of moving 16-bit values among components of the CPU

Chapter 23: CPU Control Signals
    ALU, register array, latches are connected to each other and RAM through data busses
        8-bit data bus that ferries bytes among components
        16-bit address bus used for memory address
    The busses are main source of connection between components
        Components also connected via control signals
            They control components to execute instructions stored in memmory
    Types of control signals
        Signals that put value on one of the two busses
        Signals that save a value from one of the two busses
    How CPU executes instructions stored in memory
        Synchronization of Enable inputs and Clock inputs
        This is the key of where hardware and software meet
        CPU control signals are the strings of the puppeteer
    How the CPU executes instructions
        First byte is the operation code (opcode)
            Some may contain more than one
        CPU uses value called program counter to address memory and move instruction to instruction latches
        Five steps to process first instructin
            1) Address RAM w/program counter value of 0000h and store value in instruction latch 1
                Requires Program Counter Enable, Ram Data Out Enable, Incrementer-Decrementer Clock, Instruction Latch 1 Clock
            2) Increments program counter
                Just involves address bus: increment enable and then program counter clock
            3 and 4) Same as first and second but they access the byte at memory address 0001h and save it in Instruction Latch 2
            5) Execution of the instruction
                Instruction Latch 2 Enable and Accumulator Clock (save value on data bus in accumulator)
    Machine cycles, the steps we've been describing
        Instruction bytes accessed from memory in one cycle that is followed by another that increments the program counter
        Instruction execution requires one or two machine cycles depending on the instruction
    Decoding the opcode
        Connect output bits of Instruction Latch 1 to three decoders
</pre>
    