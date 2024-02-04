# Imperative Way
<details>
  <summary>Click me</summary>
  
  ### Heading
  1. Foo
  2. Bar
     * Baz
     * Qux

  ### Some Javascript
  ```sh
  kubectl run mypod --image=nginx:alpine
  ```
</details>
<details>
	<summary>
		Question 1: Create a pod with name "mypod" using nginx:alpine image.
	</summary>
	### Answer 
	```sh
	kubectl run mypod --image=nginx:alpine
	```
</details>

```sh
kubectl run mypod --image=nginx:alpine
```

#### Question 2: Create a pod with name "pod-2" using the redis image with label name=pod-2

```sh
kubectl run pod-2 --image=redis --labels=name=pod-2
```

#### Question 3: Create a pod with name "nginx" and image nginx, expose it on Port 8080

```sh
kubectl run nginx --image=nginx --port=8080
```
