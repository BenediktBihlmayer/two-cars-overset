// Generated for OpenCFD OpenFOAM v2406. SI units.
FoamFile
{
    version 2.0;
    format ascii;
    class volScalarField;
    object nut;
}

dimensions [0 2 -1 0 0 0 0];
internalField uniform 0.0167705098312;
boundaryField
{
    #includeEtc "caseDicts/setConstraintTypes"
    overset { type overset; }
    sideMin { type symmetryPlane; }
    sideMax { type symmetryPlane; }
    top { type symmetryPlane; }
inlet { type calculated; value uniform 0.0167705098312; }
outlet { type calculated; value uniform 0.0167705098312; }
"(ground|movingGround|car[12]_.*)" { type nutkWallFunction; value uniform 0.0167705098312; }
}
