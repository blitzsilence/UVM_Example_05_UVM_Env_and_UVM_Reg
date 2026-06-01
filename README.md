# UVM_Example_UVM_Register_Model

## Intro
參考書籍 張強 《UVM实战》第六章 UVM_Sequence 及第七章 UVM_Register

建立一個帶有Register Model的UVM測試平台

## Verification Environment
```
    Project_root
    │
    ├── README.md
    │    
    ├── doc
    │   └── xxxx
    │
    ├── rtl
    │   └── dut.sv
    │
    ├── sim
    │   ├── Makefile
    │   └── runlist
    │ 
    └── tb
        ├── env
        │   ├── agent.sv
        │   ├── env.sv
        │   ├── monitor.sv
        │   ├── ref_model.sv
        │   ├── scoreboard.sv
        │   ├── sequencer.sv
        │   ├── sequencer.sv
        │   └── transaction.sv
        │ 
        ├── interface
        │   └── interface.sv
        │
        ├── package
        │   └── env_pkg.sv
        │ 
        ├── register
        │   ├── adapter.sv
        │   └── reg_model.sv
        │ 
        ├── sequence
        │   ├── sequence_bus.sv
        │   ├── sequencer_dut.sv
        │   ├── v_sequence.sv
        │   └── v_sequencer.sv
        │
        ├── testcase
        │   ├── base_test.sv
        │   ├── my_case1.sv
        │   └── my_case1.sv
        │        
        └── top
            ├── tb_top.sv
            ├── rtl.f
            └── tb.f
```

## Makefile excution note
make comp 

make all TESTNAME=basetest

make sim TESTNAME=my_case0

make sim TESTNAME=my_case1


## UVM testbench topology
```
------------------------------------------------------------------
Name                       Type                        Size  Value
------------------------------------------------------------------


------------------------------------------------------------------
```
