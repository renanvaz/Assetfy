# Assetfy (For Starling Framework)
Assetfy is a open source library thet converts flash MobieClips into Starling data object formats.

    types
        Bitmap // Flaten container and converts to Starling Bitmap Object
        Image // Flaten container and converts to Starling Image Object
        MovieClip // Converts Flash MovieClip into Starling MovieClips Object
            - frame (frame-number / label name)
            - loop (animation name, mode [reverse, normal])
            - play (animation name, mode [reverse, normal])
            - stop ()
            - set/get FPS
            - add (SheetData)

    Classes
        Bitmap
        MovieClip
            - frame (frame-number / label name)
            - loop (animation name, mode [reverse, normal])
            - play (animation name, mode [reverse, normal])
            - stop ()
            - add (SheetData)
        MovieClipData
            - name
            - frames (array | frame number from, frame number to)

    Assetfy
        - me (DisplayObject, type [Bitmap, MovieClip])
        - content (DisplayObjectContainer with Assetfy childs interface class):Object
