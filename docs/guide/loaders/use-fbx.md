# useFBX

A composable that allows you to easily load glTF models into your **TresJS** scene.

## Usage

```ts
import { useFBX } from '@tresjs/cientos'

const model = await useFBX('/models/AkuAku.fbx')
```

Then is as straightforward as adding the scene to your scene:

```html{3}
<TresCanvas shadows alpha>
  <Suspense>
    <primitive :object="scene" />
  </Suspense>
</TresCanvas>
```
