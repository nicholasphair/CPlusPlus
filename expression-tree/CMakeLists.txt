cmake_minimum_required(VERSION 3.16)
project(expression_tree)

set(CMAKE_CXX_STANDARD 17)

include_directories(.)

add_executable(expression_tree
        Component_Node.cpp
        Component_Node.h
        Composite_Add_Node.cpp
        Composite_Add_Node.h
        Composite_Binary_Node.cpp
        Composite_Binary_Node.h
        Composite_Divide_Node.cpp
        Composite_Divide_Node.h
        Composite_Multiply_Node.cpp
        Composite_Multiply_Node.h
        Composite_Negate_Node.cpp
        Composite_Negate_Node.h
        Composite_Subtract_Node.cpp
        Composite_Subtract_Node.h
        Composite_Unary_Node.cpp
        Composite_Unary_Node.h
        Evaluation_Visitor.cpp
        Evaluation_Visitor.h
        Event_Handler.cpp
        Event_Handler.h
        Expression_Tree.cpp
        Expression_Tree.h
        Expression_Tree_Command.cpp
        Expression_Tree_Command.h
        Expression_Tree_Command_Factory.cpp
        Expression_Tree_Command_Factory.h
        Expression_Tree_Command_Factory_Impl.cpp
        Expression_Tree_Command_Factory_Impl.h
        Expression_Tree_Command_Impl.cpp
        Expression_Tree_Command_Impl.h
        Expression_Tree_Context.cpp
        Expression_Tree_Context.h
        Expression_Tree_Event_Handler.cpp
        Expression_Tree_Event_Handler.h
        Expression_Tree_Iterator.cpp
        Expression_Tree_Iterator.h
        Expression_Tree_Iterator_Impl.cpp
        Expression_Tree_Iterator_Impl.h
        Expression_Tree_State.cpp
        Expression_Tree_State.h
        getopt.cpp
        getopt.h
        Interpreter.cpp
        Interpreter.h
        Leaf_Node.cpp
        Leaf_Node.h
        main.cpp
        Options.cpp
        Options.h
        Print_Visitor.cpp
        Print_Visitor.h
        Reactor.cpp
        Reactor.h
        Refcounter.cpp
        Refcounter.h
        Typedefs.h
        Visitor.cpp
        Visitor.h)
