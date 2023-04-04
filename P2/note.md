# Show learning MAC adress with dynamic multicast
bridge -c fdb show dynamic

# Execute command in the network namespace of the container from VM host
sudo nsenter -t [PID_PROCESS_RUNNING_INSIDE_CONTAINER] -n ip -d link show vxlan10