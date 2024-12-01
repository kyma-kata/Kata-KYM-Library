# About

This sound flips or folds waves that exceed the -1 to 1 range.  This is similar to AddWrap but doesn’t support multiple inputs.  To create a wrapping mixer add sounds and attenuate each sound by the total number of inputs. For example, 1/# of inputs.  Then set the minimum value to the number of inputs. 

This sound works by reducing the internal resolution and using the ‘overflow’ bits to wrap down.  This results in the primary audio channel resolution to be 24-bits.  It also limits the maximum number of folds to 255 (8-bits)

There are two variations with the wavefolder version allowing for sample rate modulation of the drive parameter towards the maximum wrap amount.