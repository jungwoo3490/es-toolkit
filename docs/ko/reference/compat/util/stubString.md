# stubString

::: info
이 함수는 호환성을 위한 `es-toolkit/compat` 에서만 가져올 수 있어요. 대체할 수 있는 네이티브 JavaScript API가 있거나, 아직 충분히 최적화되지 않았기 때문이에요.

`es-toolkit/compat`에서 이 함수를 가져오면, [lodash와 완전히 똑같이 동작](../../../compatibility.md)해요.
:::

빈 문자열을 반환해요.

## 인터페이스

```typescript
function stubString(): '';
```

### 반환 값

(`''`): 빈 문자열.

## 예시

```typescript
stubString(); // Returns ''
```