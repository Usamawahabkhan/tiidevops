
1. FOUNDATIONS & PHILOSOPHIES
	• DevOps → Culture combining development and operations to deliver software faster and more reliably.
	• Agile → Iterative software delivery approach using short cycles for rapid feedback.
	• Lean → Maximizing value while eliminating waste and delays.
	• ITSM (ITIL) → Framework for delivering and managing IT services efficiently.
	• Change Management → Controlled process for introducing changes into systems.
	• Kaizen → Continuous small improvements to processes and systems.
	• Systems Thinking → Understanding how components interact within a whole system.
	• Theory of Constraints → Identifying and optimizing bottlenecks in workflows.
	• Value Stream Thinking → Optimizing the flow from idea to customer value.
	• Product Mindset → Treating software as continuously evolving products.

2. DEVOPS LIFECYCLE
	• Plan → Define requirements and priorities.
	• Code → Develop application source code.
	• Build → Compile and package code into artifacts.
	• Test → Validate functionality and quality.
	• Release → Prepare builds for deployment.
	• Deploy → Push applications to environments.
	• Operate → Run and manage applications in production.
	• Monitor → Track system performance and health.
	• Feedback Loop → Continuous learning from production insights.

3. CORE PRACTICES
	• CI (Continuous Integration) → Frequent code integration with automated testing.
	• CD (Continuous Delivery) → Code always ready for production release.
	• Continuous Deployment → Automatic release to production without manual approval.
	• CI/CD Pipeline → Automated workflow from code commit to deployment.
	• Infrastructure as Code (IaC) → Managing infrastructure using code.
	• Configuration as Code → Managing system configs via code files.
	• Policy as Code → Enforcing governance rules via code.
	• GitOps → Using Git as the source of truth for deployments.
	• Trunk-Based Development → Developers merge small changes frequently.
	• Feature Branching → Isolating features in separate branches.
	• Release Management → Planning and controlling software releases.

4. ARCHITECTURE
	• Monolith → Single unified application.
	• Microservices → Small independent services communicating via APIs.
	• SOA → Services interacting across systems.
	• Event-Driven Architecture → Systems reacting to events/messages.
	• Serverless → Running code without managing servers.
	• Cloud-Native → Designed for cloud scalability and resilience.
	• API-First → Designing APIs before implementation.

Deployment Strategies
	• Blue-Green → Switch traffic between identical environments.
	• Canary → Gradual rollout to a small user subset.
	• Rolling Deployment → Incrementally replacing instances.
	• Shadow Deployment → Testing in production with hidden traffic.
	• Feature Flags → Toggle features without redeploying.

Resilience Patterns
	• Circuit Breaker → Stop failing calls to prevent system overload.
	• Bulkhead → Isolate failures between components.
	• Retry Pattern → Automatically retry failed operations.
	• Timeouts → Prevent indefinite waits.
	• Graceful Degradation → Reduce functionality instead of full failure.
	• Chaos Engineering → Inject failures to test resilience.

5. CLOUD & INFRA
	• IaaS → Infrastructure provided as a service.
	• PaaS → Platform for building applications.
	• SaaS → Software delivered via cloud.
	• Multi-Cloud → Using multiple cloud providers.
	• Hybrid Cloud → Mix of cloud and on-prem systems.
	• High Availability → Systems designed for minimal downtime.
	• Fault Tolerance → Systems continue working during failures.
	• Elasticity → Auto-scaling resources based on demand.
	• Load Balancing → Distributing traffic across servers.
	• CDN → Delivering content closer to users.

6. CONTAINERS & KUBERNETES
	• Docker → Platform to package applications into containers.
	• Container → Lightweight runtime environment for apps.
	• Kubernetes → Orchestrates container deployment and scaling.
K8s Concepts
	• Pod → Smallest deployable unit in Kubernetes.
	• Node → Machine running pods.
	• Cluster → Group of nodes.
	• Deployment → Manages replicas of pods.
	• Service → Exposes pods for communication.
	• Ingress → Manages external access.
	• Namespace → Logical cluster segmentation.
	• ConfigMap → Stores configuration data.
	• Secrets → Stores sensitive data.
	• Helm → Package manager for Kubernetes.

7. SECURITY (DEVSECOPS)
	• DevSecOps → Integrating security into DevOps lifecycle.
	• Zero Trust → Always verify, never trust by default.
	• IAM → Managing identities and permissions.
	• Secrets Management → Securing credentials.
	• Encryption → Protecting data from unauthorized access.

Security Testing
	• SAST → Static code vulnerability analysis.
	• DAST → Testing running applications for flaws.
	• SCA → Checking third-party dependencies.
	• Pen Testing → Simulating attacks to find risks.

8. OBSERVABILITY
	• Observability → Ability to understand system internals via outputs.
	• Telemetry → Collection of system data.
Three Pillars
	• Logs → Event records.
	• Metrics → Numeric system measurements.
	• Traces → Request journey tracking.

Monitoring Models
	• Golden Signals → Latency, traffic, errors, saturation.
	• RED → Rate, errors, duration.
	• USE → Utilization, saturation, errors.

9. SRE
	• SRE → Engineering approach to operations.
	• Error Budget → Allowed failure before slowing releases.
	• Toil → Manual repetitive operational work.
SLO Framework
	• SLI → Measured performance metric.
	• SLO → Target reliability goal.
	• SLA → Contractual reliability commitment.

10. INCIDENT MANAGEMENT
	• Incident → Unplanned disruption or service degradation.
	• SEV Levels → Incident priority classification.
	• On-call → Engineers available for incidents.
	• Runbook → Predefined recovery steps.
	• War Room → Real-time incident coordination.
	• Postmortem → Incident analysis without blame.
	• RCA → Root cause identification.

11. DORA METRICS
	• Deployment Frequency → How often deployments occur.
	• Lead Time → Time from commit to production.
	• Change Failure Rate → % of failed changes.
	• MTTR → Time to restore service.

12. RELIABILITY METRICS
	• Availability → % uptime.
	• Latency → Response delay time.
	• Throughput → Number of processed requests.
	• Error Rate → Failed requests percentage.
	• Apdex → User satisfaction score.

13. FLOW METRICS
	• Flow Time → Idea to delivery time.
	• Flow Efficiency → Active vs wait time.
	• WIP → Work in progress.
	• Cycle Time → Work start to finish duration.

14. TOOLCHAIN
	• Git → Version control system.
	• CI Tools → Automate builds and tests.
	• Artifact Repo → Store build outputs.

15. DATA & AI OPS
	• DataOps → Automating data pipelines.
	• MLOps → Managing ML lifecycle.
	• AIOps → AI-driven IT operations.
	• Model Drift → Degrading ML performance over time.

16. FINOPS
	• FinOps → Managing cloud costs efficiently.
	• Cost Allocation → Tracking costs by usage.
	• Rightsizing → Optimizing resource usage.

17. TEAM DESIGN
	• Stream-aligned Team → Focused on delivering value streams.
	• Platform Team → Provides developer infrastructure.
	• Enabling Team → Helps others improve capabilities.
	• Subsystem Team → Handles complex components.

18. CULTURE
	• CALMS → Culture, Automation, Lean, Measurement, Sharing.
	• Psychological Safety → Safe to speak and fail.
	• DevEx → Developer productivity and satisfaction.
	• Westrum Model → Organizational culture classification.

19. ENGINEERING PRACTICES
	• Code Review → Peer validation of code.
	• Pair Programming → Two developers working together.
	• Refactoring → Improving code without changing behavior.
	• Tech Debt → Cost of poor design decisions.

20. GOVERNANCE
	• Risk Management → Identifying and mitigating risks.
	• Audit Trail → Record of system changes.
	• Compliance → Meeting regulatory requirements.

21. PLATFORM ENGINEERING
	• IDP → Internal developer platform.
	• Golden Path → Best-practice development workflows.

22. ANTI-PATTERNS
	• Manual Deployments → Non-automated releases.
	• Big Batches → Large risky releases.
	• Silos → Isolated teams.
	• Hero Culture → Dependence on individuals.

23. MATURITY MODEL
	• Ad-hoc → Optimized → Evolution from chaos to automation.

