# Basic ACE Medical
This guide is aimed primarily towards players who have not used ACE Medical previously, but also covers more general topics that helps anyone become a more effective part of the squad.

## ACE Medical

ACE Medical is part of the ACE mod, which aims to increase the realism of ArmA 3 Gameplay.

ACE Medical extends the vanilla ArmA 3 health model and adds several additional factors, such as different types of wounds, bleeding, heart rate, blood pressure, and so on. On top of this there are also an extended arsenal of treatments available to the player, and knowing which one to choose in what circumstances is part of the fun.

Lets begin.

## What to expect
  ACE Medical is quite advance, and may be a little bit overwhelming at first, but it really comes down to a rather simple gameloop.

  `Damage -> Wounds -> Secondary Effects -> Treatment`

  Compared to vanilla ArmA 3 only the `wounds` are really new, however its worth noting that all other parts have been heavily extended as well.

  We will go over each stage briefly.


### Damage
  _Sources of damage determine wound types_
  
### Wounds
  There are many different types of wounds simulated in ACE Medical, from scraped knees to large velocity wounds. When damage is taken ACE determines the types, sizes, and ammounts of wounds to apply to the player based on the type of damage. For now all you really need to know is that some wounds are bigger than other, and therefore will require more urgent attention. If you are hit in the arm with a .50 cal you might want to take care of that much sooner than if you take a 9mm to your chestplate. 

### Secondary Effects
  Wounds in turn will cause seconday effects on the player.
  
  This is where the health model comes into play. While vanilla ArmA 3 models health closer to a common HP system where a single number represents the health of the unit, ACE instead models parameters such as heartrate, bloodpressure, and pain. These are all interlinked with eachother and in turn affect the overall state of the players health, such as unconciosness, stamina, accuracy, and even vision.

  These seconday and tertiary effects are the result of taking damage, and the goal of the ACE Medical gameplay loop is to revert these effects and "Heal" the unit.

### Treatments
  Treatments in vanilla ArmA 3 is mostly a one-and-done thing, what with FAKs and Medkits. In ACE Medical this is much, much more neuanced and the core gameplay of the system.

  Each wound and effect are best treated by a specific treatment option, and more often than not the treatments come with both pros and cons, so choosing the correct one can make a huge difference. For non-medics however there is room for some amount of generalisation to make it easier.

  Treatments can be broken down into three categories
  - Bandages
  - Medications
  - Specialized

  Bandages are the most straight forward. You apply a bandage to a wound to stop it from bleeding. There are however several different types of bandages to choose from but we will cover which you need to care about later.

  Medications are a little bit more tricky. This category mainly refers to `Morphine` and `Epinephrine`. These affect not the wounds but rather target the secondary effects by altering the vital parameters. We will cover how to use them and what to be carefull of later, but for now just remember that you want to be carefull with these.

  The Specialized category include items such as `Tourniqets`, `Splints`, and `IVs`. These items are designed to do a single task, and are pretty straight forward. We will discuss the workings of these later as well. There are more specialized items available, but as a non medic these three are the ones you need to care about.


## Interacting with ACE Medical
_How to interact with ACE Medical as a player_
### How to Access
  EXPLANATION TEXT
  ![image info](../assets/medical/medicalMenu.png)

### How to Navigate
### How to Read

## Evaluating damage
_How to efficiently triage casualties_
### Is the patient conscious
### How hurt is the patient
### Does the patient have vitals
### How much is the patient bleeding
### How long ago did the patient receive damage

## Treatment
_How to stabilize and treat a casualty_
### Stopping bleeding
### Restoring vitals
  - Also explain the death timer here, and how CPR resets it even if there is no pulse
### Controlling pain
### Fixing fractures
### Regaining consciousness

## Risks of medications
_What not to do with morphine and epi_
### Morphine
### Epinephrine

## How to act as a non-medic
_How one should act to not get left behind while uncon_
### What to bring
### What to say
### What to do
### Looking out for team members.
### Making it easier for team members to look out for you.
### How to help your medic help you
