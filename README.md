# BasicPID

Basic PID is a fundamental PID frame for contorlling.

## Install
1. Simple copy ``` BasicPID.h & BasicPID.cpp ``` to your workspace folder.
2. Remember check Dependence.

## Dependency
Works with ``` C++ 98 ``` or lateset. 
BasicPID includes only ``` std::queue ``` and ``` cstdio (alternative) ```.

## Usage

1. declare a BasicPID type: 

    ``` BasicPID demoPID; ```

2. set PID paraments:

    ``` demoPID.setPara( kp, ki, kd); ```
    
    or set when init

    ``` BasicPID demoPID( kp, ki, kd); ```

3. update Error Value by function:

    ``` demoPID.push( {inputValue} ); ```

4. get output by member varible:

    ``` demoPID.outputValue; ```


## Contirbutors

[WuYuanhun](https://github.com/WuYuanhun): Liu Cetian

Wang Bingyao