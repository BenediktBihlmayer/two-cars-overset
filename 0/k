// Generated for OpenCFD OpenFOAM v2406. SI units.
FoamFile
{
    version 2.0;
    format ascii;
    class volScalarField;
    object k;
}

dimensions [0 2 -2 0 0 0 0];
internalField uniform 0.09375;
boundaryField
{
    #includeEtc "caseDicts/setConstraintTypes"
    overset { type overset; }
    sideMin { type symmetryPlane; }
    sideMax { type symmetryPlane; }
    top { type symmetryPlane; }
inlet { type fixedValue; value uniform 0.09375; }
outlet { type inletOutlet; inletValue uniform 0.09375; value uniform 0.09375; }
"(ground|movingGround|car[12]_.*)" { type kqRWallFunction; value uniform 0.09375; }
}
