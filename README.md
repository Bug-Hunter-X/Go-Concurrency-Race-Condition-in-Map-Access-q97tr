# Go Concurrency Race Condition

This example demonstrates a common race condition in Go when multiple goroutines concurrently access and modify a shared map without proper synchronization.  The program attempts to sum numbers concurrently, but the result is unpredictable due to data races.