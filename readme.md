# About the Marathon Infinity Multiplayer Enhancement Physics

The original Marathon weapons were not really designed with people in mind. They were designed to be effective against slow and stupid aliens that could not dodge shots and could not operate their weaponry while they were being blasted by the player. Human players are a bit more intelligent, and faster than that.

This physics model addresses those changes and has undergone thorough balance testing during its development. Weapon switching delay is now nearly non-existant and random damage has been taken out of the game. Weapons that would normally never see action in an otherwise SPNKR filled multiplayer match can now go up against a SPNKR armed player under the right conditions.  

## Goals

- Strategic application of weapons. No dead guns. Every gun should serve a purpose.
- Eliminate randomness. It should be possible to estimate your opponents remaining health.
- Combine weapons to kill more effectively. Quick weapon switching.
- Balance. There should be no gun to rule them all. 

## Notes

- This physics model was not designed with multiplayer modes that include monsters in mind.
- Beta testing was primarily done with one versus one, Every Man for Himself. If you play different kind of game modes and notice any issues, please file a bug report or e-mail us as noted below.

# Changes

## Overall

- **Damage Random** set to **0** on all weapons. Therefor every weapon sees **base damage** increase by **1/2** of the original **damage random** value.
- **Ready time** (time between weapon switching) set to **1**.

## Fists

- **Damage Base** increased from **50** to **55**.

Fists are the same as before excluding Damage Random/Base change. Use them for the perfect humiliation effect at extreme close range.

## .44 Magnum Pistols

- **Damage Base** increased from **20** to **24**.
- **Radius** increased from **0** to **400**.
- **Recoil** decreased from **10** to **0**.

Pistols are now extremely easy to hit with. Use them to easily finish off a wounded opponent from mid to long range.

## MA-75B Assault Rifle

- Primary Trigger
	- **Theta Error** decreased from **10** to **7**.
	- **Damage Base** increased from **9** to **12**.
- Secondary Trigger
	- **Damage Base** decreased from **80** to **70**.
	- **Area of effect** increased from **768** to **1024**.
	- **Speed increased** from **256** to **400**.
	- **Double affected by gravity** box **checked**.
	
The assault rifle is now a lot more accurate than we have (grudgingly) grown accustomed to. The grenades are now nearly two times faster than previously which along with his accuracy makes it a lot more usable at short to mid range.

## SPNKR Rocket Launcher

- **Damage Base** increased from **250** to **275**.

No changes apart from Damage Base/Random changes. All around killer weapon for any situation although best at mid-range. Remember, Don't go running blindly into a battle with the SPNKR against other weapons as they are not the harmless pea shooters anymore you had grown accustomed to.

## Zeus Class Fusion Pistol

- Primary Trigger
	- **Damage Base** increased from **30** to **45**.
	- **Speed** increased from **256** to **512**.
- Secondary Trigger
	- **Damage Type** set from **Fusion Bolt** to **Energy Drain**.
	- **Damage Base** increased from **30** to **260**.
	- **Speed** increased from **256** to **768**.

The Fusion Pistol is back, but this time inspired by the plasma pistol from Halo. The Bolts are now fast enough to actually make a difference, and secondary trigger now drains 260 health from your opponent, acting as a great way to take out opponents shields. Works well at short and mid range, in relatively flat areas.

Note that the secondary trigger has quite a kick for the unlucky receiver. It can stun him for a second or two so be quick to switch to a more fitting weapon to finish him off.

## TOZT-7 Flamethrower

- **Damage Base** increased from **8** to **10**.

No changes apart from Damage Base/Random adjustments. It is still a fearful weapon to be used at extreme close range.

## Alien Weapon

- **Damage Base** increased from **20** to **24**.
- **Speed** increased from **256** to **512**.

The speed increase now makes the alien weapon actually usable at short and mid range. And also makes it a good way to clear an area.

## WSTM Shotguns

- **Damage Base** increased from **20** to **22**.

No changes apart from Damage Base/Random adjustments. The shotguns still work beautifully at close and mid range. Also fitting for long range if you are finishing off a wounded opponent.

## KKV-7 SMG Flechette

- **Automatic** checkbox **unchecked**.
- **Damage Base** increased from **9** to **253**.
- **Speed** increased from **1024** to **2048**.
- **Firing sound** changed from **"SMG firing (Inf only)"** to **"Cyborg Attack"**.
- **Rounds/magazine** changed from **32** to **1**.
- **Ticks/round** increased from **-1** to **15**.
- **Recovery Ticks** changed from **0** to **15**.
- **Recoil Magnitude** increased from **5** to **20**.
- **Theta error** decreased from **3** to **0**.
- **Burst count** decreased from **2** to **0**.

The biggest change in the arsenal. The SMG is now acting as a sniper with one bullet per magazine. The damage and accuracy makes this the most powerful gun in the game. But if you miss, you are doomed.

## Bug Reports
Thoughts? Bug Reports? Hatemail? Ideas?  
Send them to johannesg@johannesg.com or file an issue at https://github.com/johannesgunnar/Marathon-Infinity-Multiplayer-Enhancement-Pack/issues

# Credits
Jóhannes Gunnar Þorsteinsson  
http://www.johannesg.com  
johannesg@johannesg.com

Göran Svensson  
goransvensson@gmail.com
