git push --set-upstream origin main

<ItemGroup>
    <!-- AWS Elastic Beanstalk stuff https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create-deploy-dotnet-core-linux.html -->
    <None Include=".ebextensions\newrelic.config" CopyToOutputDirectory="Always" />
</ItemGroup>

not cd ./web && zip -r ../web.zip *
cd ./web && zip -r ../web.zip .ebextensions *

type of API keys from newrelic

newrelic infra and dotnet agents

testing