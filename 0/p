// Generated for OpenCFD OpenFOAM v2406. SI units.
FoamFile
{
    version 2.0;
    format ascii;
    class volScalarField;
    object p;
}

dimensions [0 2 -2 0 0 0 0];
internalField uniform 0;
boundaryField
{
    #includeEtc "caseDicts/setConstraintTypes"
    overset { type overset; }
    sideMin { type symmetryPlane; }
    sideMax { type symmetryPlane; }
    top { type symmetryPlane; }
inlet { type zeroGradient; }
outlet { type fixedValue; value uniform 0; }
"(ground|movingGround|car[12]_.*)" { type zeroGradient; }
}
