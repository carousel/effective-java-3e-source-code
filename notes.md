# Contents
    1.Introduction
    2.Creating and Destroying Objects 
        Static factory
        Builder
        Singleton
        Private constructor (noninstantiability)
        DI
        Avoid redundant objects creation
        Eliminite obsolete references
        Avoid finalizers and cleaners
    3.Methods Common to All Objects
        equals contract
        hashCode contract
        override toString
        override clone judiciouscly
        implement Comparable
    4.Classes and Interfaces
        minimize accessability
        accessor methods
        minimize mutability
        composition over inheritance
        document inheritance
        prefer interfaces to abstract classes
        interface for types
        prefer static member classes
    5.Generics
        don't use raw types
        eliminate unchecked warnings
        Prefer lists to arrays                                                        
        Favor generic types                                                         
        Favor generic methods                                                    
        Use bounded wildcards to increase API flexibility        
        Combine generics and varargs judiciously                     
        Consider typesafe heterogeneous containers
    6.Enums and Annotations
        Use enums instead of int constants                               
        Use instance fields instead of ordinals                            
        Use EnumSet instead of bit fields                                    
        Use EnumMap instead of ordinal indexing                       
        Emulate extensible enums with interfaces                      
        Prefer annotations to naming patterns                            
        Consistently use the Override annotation                     
        Use marker interfaces to define types                            
    7.Lambdas and Streams
        Prefer lambdas to anonymous classes                            
        Prefer method references to lambdas                              
        Favor the use of standard functional interfaces              
        Use streams judiciously                                                  
        Prefer side-effect-free functions in streams                    
        Prefer Collection to Stream as a return type                   
        Use caution when making streams parallel                    
    8.Methods
        Check parameters for validity                                          
        Make defensive copies when needed                              
        Design method signatures carefully                                
        Use overloading judiciously                                            
        Use varargs judiciously                                                    
        Return empty collections or arrays, not nulls                  
        Return optionals judiciously                                            
        Write doc comments for all exposed API elements        
    9.General Programming
         Minimize the scope of local variables                              
        Prefer for-each loops to traditional for loops                  
        Know and use the libraries                                              
        Avoid float and double if exact answers are required  
        Prefer primitive types to boxed primitives                      
        Avoid strings where other types are more appropriate    
        Beware the performance of string concatenation            
        Refer to objects by their interfaces                                  
        Prefer interfaces to reflection                                          
        Use native methods judiciously                                       
        Optimize judiciously                                                        
        Adhere to generally accepted naming conventions          
    10.Exceptions
        Use exceptions only for exceptional conditions              
        Use checked exceptions for recoverable conditions and runtime exceptions for programming errors                    
        Avoid unnecessary use of checked exceptions                
        Favor the use of standard exceptions                               
        Throw exceptions appropriate to the abstraction             
        Document all exceptions thrown by each method           
        Include failure-capture information in detail messages   
        Strive for failure atomicity                                              
        Don’t ignore exceptions                                                  
    11.Concurrency
        Synchronize access to shared mutable data                    
        Avoid excessive synchronization                                    
        Prefer executors, tasks, and streams to threads              
        Prefer concurrency utilities to wait and notify            
        Document thread safety                                                  
        Use lazy initialization judiciously                                  
        Don’t depend on the thread scheduler                            
    12.Serialization
        Prefer alternatives to Java serialization                          
        Implement Serializable with great caution                
        Consider using a custom serialized form                        
        Write readObject methods defensively                        
        For instance control, prefer enum types to readResolve                                                                  
        Consider serialization proxies instead of serialized instances                                                                          

