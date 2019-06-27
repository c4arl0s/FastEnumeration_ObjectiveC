# FastEnumeration_ObjectiveC
FastEnumeration_ObjectiveC

- Iterate over a collection

# Ways to each programming paradigm iterate over a collection.

- Procedural: increments a pointer within a loop
- Object Oriented: applies a function or block to each object in a collection.
- Functional works through a data structure recursively.

# Basic Syntax:

``` objective-c
for ( classType variable in expression )
{
   statements
}
```

# Fast Enumeration Forward with Array

``` obejctive-c
//
//  ViewController.m
//  FastEnumerationForwardWithArray
//
//  Created by Carlos Santiago Cruz on 6/27/19.
//  Copyright © 2019 Carlos Santiago Cruz. All rights reserved.
//

#import "ViewController.h"

@interface ViewController ()

@end

@implementation ViewController

- (void)viewDidLoad {
    [super viewDidLoad];
    
    NSArray *array = [NSArray arrayWithObjects:@"valvula", @"regulador", @"manometro", nil];
    for (NSString *element in array) {
        NSLog(@"product: %@", element);
    }
}
```


``` console
2019-06-27 01:13:49.190803-0500 FastEnumerationForwardWithArray[1774:147030] product: valvula
2019-06-27 01:13:49.191099-0500 FastEnumerationForwardWithArray[1774:147030] product: regulador
2019-06-27 01:13:49.191287-0500 FastEnumerationForwardWithArray[1774:147030] product: manometro
```



@end






