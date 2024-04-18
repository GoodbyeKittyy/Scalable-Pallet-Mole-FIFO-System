## Solution Explained

This is a simple Flexsim model that implements functionality for "pallet moles." These are small vehicles that move pallets forward in a racking system. The targeted behavior is a FIFO storage mechanism like what you would see in gravity flow racks. However, for incredibly deep storage, a gravity flow mechanism would result in unacceptable pressures exerted on the pallets at the front of the rack, especially when pallets collide with each other as they roll down the slot. These pallet moles solve these issues. They provide the forward movement that enables FIFO storage, without the unacceptable pressures that come with gravity flow.

The functionality is implemented as two object process flows, one for the rack, and one for the pallet mole. As such, it is scalable to higher numbers of racks and moles. Just add the set of racks/moles that your model uses, and then make sure those objects are attached as instances of their respective object process flow.

Moles can be moved between different slots in the racking system. If a mole needs to move to a different slot, it will request transport from a team of fork lifts. The fork lift picks the mole up from the slot, and moves it to the destination slot.

</br></br>

## 3D Animation 

https://github.com/GoodbyeKittyy/Scalable-Pallet-Mole-FIFO-System/assets/161730857/6791c90d-004f-4432-8204-f9e15d15e632

</br></br>


</br></br>

## Live Process Flowcharts

https://github.com/GoodbyeKittyy/Scalable-Pallet-Mole-FIFO-System/assets/161730857/9783420e-02b7-4c31-b843-3f1b9a3df5a4



