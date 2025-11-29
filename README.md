# 💊 CapRack

![A CapRack NAS](./assets/nas-front.jpg)

CapRack is a modular 10-inch server rack mounting system that allows you to install small footprint equipment in your [mini rack](https://github.com/geerlingguy/mini-rack) in an aesthetic way.

Size of 1U in a mini rack is typically 222.25mm x 44.45mm.
Most devices on the shelf that homelabbers want to put in their mini rack, like mini PCs or SBCs, do not fit in 1U out of the box.
Mounting the devices on a open rack tray is a common solution.
For nerds who care more about appearance, CapRack is now a better alternative.

The concept of CapRack is simple: split 1U vertically into 2 0.5U CapRack modules.
CapRack modules all follow the same standard to connect each other.
**Connect any 2 CapRack modules into a 1U mini rack module.**
Some examples:

- Connect a mini PC module with a 2.5-inch disk mount module, you get a 1U mini NAS.
  ![Mini NAS in 1U](./assets/mini-nas.jpg)
- Compose a mini PC module with and a mini switch module, you get a decent, 1U, custom home router.
- Simple connect 2 raspberry pi modules to create a 2-node pi cluster. Repeat it you can get a 4-node cluster in 2U. This is not the most space-efficient way, compared to solutions like [pi slice rack](https://github.com/Coole-Guus/pi-slice-rack). But it gives you more flexibility if you are not Jeff Geerling and only have 1~4 pis to mount. E.g. You have only 3 pis to mount, you can still fit them in 2U by composing 3 pi modules + 1 mini switch module, and connect them with ethernet.

## How to connect 2 CapRack modules

CapRack is designed to be connected with M6 screws. As M6 screws are common in server rack mounting, they are easy to access to people who own a rack.

To connect 2 CapRack modules, you need **2 M6 screws (at least 12mm long) and 2 M6 hex nuts**.

1. Prepare 2 M6 screws, 2 M6 hex nuts, and the 2 CapRack modules you are going to connect.
   ![](./assets/connect-0.jpg)
2. Slide the 2 modules from the side.
   ![](./assets/connect-1.jpg)
3. Slide the to the end, put a hex nut into the slot.
   ![](./assets/connect-2.jpg)
4. Screw in a M6 screw, from the other side of the panel.
   ![](./assets/connect-3.jpg)
5. Install other screw & nut in the same way to the other slot. Then you get it! The panel is ready to be installed onto your rack!
   ![](./assets/connect-4.jpg)

## CapRack Modules

### 2.5-inch disk mount

### blank panel

### blank panel with ventilation

### patch panel

### cwwk x86p5 motherboard mount

# References

- https://mini-rack.jeffgeerling.com
- https://www.amazon.com/GeeekPi-Raspberry-Adapters-Compatible-RackMate
- https://github.com/Coole-Guus/pi-slice-rack
