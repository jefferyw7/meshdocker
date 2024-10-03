# Mesh Docker
  Use the routing mesh to publish services externally to a swarm.
  Docker Engine Swarm mode makes it easy to publish ports for services to make them available to resources outside the swarm. All nodes participate in an ingress routing mesh.     The routing mesh enables each node in the swarm to accept connections on published ports for any service running in the swarm, even if there's no task running on the node.       The routing mesh routes all incoming requests to published ports on available nodes to an active container.
