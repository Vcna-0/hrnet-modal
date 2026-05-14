# hrnet-modal

Simple React modal component. Closes on Escape key or overlay click.

## Install

```bash
npm install hrnet-modal
```

## Usage

```jsx
import Modal from 'hrnet-modal'
import 'hrnet-modal/style'

function App() {
  const [isOpen, setIsOpen] = useState(false)

  return (
    <Modal isOpen={isOpen} onClose={() => setIsOpen(false)}>
      <p>Content here</p>
    </Modal>
  )
}
```

## Props

| Prop | Type | Required | Description |
|------|------|----------|-------------|
| `isOpen` | `boolean` | yes | Show/hide modal |
| `onClose` | `function` | yes | Called on Escape key or overlay click |
| `children` | `node` | yes | Modal content |

## License

MIT
