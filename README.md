# React S.O.L.I.D Principles for writing clean-code

![SOLID Principles](/src/assets/solid-principles.png)

- SRP: Single Responsibility Principle
- OCP: Open-Closed Principle
- LSP: Liskov Substitution Principle
- ISP: Interface Segregation Principle
- DIP: Dependency Inversion Principle

Basic principles: https://youtu.be/MSq_DCRxOxw
Advanced principles: https://www.youtube.com/watch?v=t_h_A6RkM7A

## Code

This Repo has examples for all principles implemented in React. Go inside `src/principle` there will be all principles there with isolated demos.

You can run the dev server using:

```bash
yarn install
yarn dev
```

Change the component in `App.tsx` with the corresponding Principle's component name to see the demo.

### Example

```tsx
function App() {
  return (
    <div className="flex min-w-full h-full justify-center items-center p-8">
      {/* <SRP /> */}
      {/* <OCP /> */}
      {/* <LSP /> */}
      <DIP />
    </div>
  );
}
```

`La branch dev no tiene funcionalidad alguna en este proyecto
`

