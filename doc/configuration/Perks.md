# Configuration File

This is the default "Messages.yml" file.

    # === [ Settings ] ===
    PerksSelector:
      Title: '&b&lPerks Selector'
      Size: 36
    Perks:
      strength:
        cost: 50.0
        slot: 11
        PotionType: strength
        duration: 5
        PerkEvent: OnHit
        Target: attacker
        locked:
          displayname: '&cStrength'
          type: BARRIER
          amount: 1
          lore:
          - '&cGain Strength when hitting your enemy for 5 seconds!'
          - ''
          - '&7Cost: &a50$'
        unlocked:
          displayname: '&aStrength'
          type: IRON_SWORD
          amount: 1
          lore:
          - '&aGain Strength when hitting your enemy for 5 seconds!'
          - ''
          - '&l&aOWNED'
    
