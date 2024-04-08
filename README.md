options:
  use-new-api: true
  on place:
  set {_block} to the placed block
  wait 20 seconds
  destroy {_block}
  play effect "ENDER_SIGNAL" at
  {_block} visible to all players
