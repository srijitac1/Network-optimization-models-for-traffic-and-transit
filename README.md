# Network-optimization-models-for-traffic-and-transit
#include <iosstream>
#include <vector>
using namespace std;
public:
int V;
vector<vector<int>>adjlist;
Graph(int vertices): V(vertices),
adjlist(vertices) {}

void addedge (int v, int w){
    adjlist[v].push_back(w);
    adjlist[w].push_back(v);
}

void diplayGraph(){
    cout<<v<<"is connected to:";
    for (int neighbour : adjlist[v]){
        cout <<"<<neighbor;
    }
    cout<<endl
}
}
};
int main(){
    Graph graph(3);

    graph.addEdge(0,1);
    graph.addEdge(1,2);

    cout<<"Graph structure:"<<endl;
    graph.displayGraph();
    return 0;
}

